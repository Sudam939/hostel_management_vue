<template>
 <div class="container">
  <div class="row m-5">
    <div class="col-md-6 my-5" style="display:flex; justify-content:center;">
      <img src="https://static.wixstatic.com/media/5229b1bab37f4162a34029310a20efbc.jpg/v1/crop/x_0,y_7,w_5184,h_3442/fill/w_358,h_237,al_c,q_90,enc_auto/Moving%20People.jpg" alt="">
    </div>
    <div class="col-md-6 p-5">
      <h3>National Student Guide</h3>
      <p>We accommodate all Nepali students, interns and working women above the age of 18, searching for a girls hostel in Kathmandu.</p>
     <button @click="$router.push({name:'national_student'})" class="btn">More Info</button>
    </div>
  </div>
 </div>

</template>

<script>
export default {
name:'CardComp'
}
</script>

<style scoped>
.container{
  text-align: center;
}
.row {
  background-image: url("https://th.bing.com/th/id/OIP.RulEbLLc9I3myhjBE2NlbwHaG4?w=165&h=180&c=7&r=0&o=5&dpr=1.3&pid=1.7");
  border-radius: 18px;
}
img{
  border: 2px;
  border-radius: 100px;
  height: 208px;
  width: 208px;
  object-fit: cover;
}

.btn{
  background: var(--themeColor);
  color: white;
}
</style>