<template>
  <template-view>
    <div class="title d-flex justify-content-center">
      <h2>Member Login</h2>
    </div>
    <div class="container">
      <div class="row">
        <div class="col-md-4"></div>
        <div class="col-md-4 py-5">
          <div class="">
            <label class="form-label"></label>
            <input type="email" class="form-control" placeholder="Email" />
          </div>
          <div class="pb-3">
            <label class="form-label"></label>
            <input type="password" class="form-control" placeholder="Password" />
          </div>
          <button type="submit" class="btn w-100">Submit</button>
          <a href="">Forgot Password</a>
        </div>
        <div class="col-md-4"></div>
      </div>
    </div>
  </template-view>
</template>

<script>
import TemplateView from "./TemplateView.vue";
export default {
  name: "LoginView",
  components: { TemplateView },
};
</script>

<style scoped>
.container {
  text-align: center;
}
.btn{
  background: var(--themeColor);
  color: white;
}
a{
  text-decoration: none;
  color: black;
}
</style>