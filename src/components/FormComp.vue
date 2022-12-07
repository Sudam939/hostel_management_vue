<template>
  <form>
    <h3>Message Us</h3>
    <div class="mb-3">
      <label class="form-label">Full Name</label>
      <input type="text" class="form-control" placeholder="Write your name here">
    </div>
    <div class="mb-3">
      <label class="form-label">Email</label>
      <input type="email" class="form-control" placeholder="Write your email here">
    </div>
    <div class="mb-3">
      <label class="form-label">Discription</label>
      <textarea style="border-radius:12px;" cols="68" rows="5" placeholder="Message us here......"></textarea>
    </div>
    
    <button type="submit" class="btn">Submit</button>
</form>
</template>

<script>


export default {
name:'FormComp'
}
</script>

<style scoped>
.btn{
  background: var(--themeColor);
  color: white;
}
</style>