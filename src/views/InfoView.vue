<template>
  <div class="">
    <div class="image">
    <h1 class="p-5">National Students</h1>
    <h5 class="m-5 px-5">We provide accommodation for students, interns and working women who are looking for accommodation in Kathmandu.</h5>
    </div>
    <info-comp/>
  </div>
</template>

<script>
import InfoComp from '@/components/InfoComp.vue'
export default {
name:'InfoView',
components:{InfoComp}
}
</script>

<style scoped>
.image{
    background-image: url("https://static.wixstatic.com/media/bddef3_80357a5ab99546d6855e46518d401f9e~mv2.jpg/v1/fill/w_1347,h_504,al_c,q_90,enc_auto/bddef3_80357a5ab99546d6855e46518d401f9e~mv2.jpg");
    height: 80vh;
    width: 100%;
    color: white;
    text-align: center;
}

</style>