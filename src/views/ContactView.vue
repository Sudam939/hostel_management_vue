<template>
  <template-view>
    <div class="title d-flex justify-content-center">
      <h2>Contact Us</h2>
    </div>
    <div class="container-fluid">
      <div class="row">
        <div class="address col-md-6">
          <h3 class="py-3">Location</h3>
          <p>
            Pashupati Marg, Bhimsengola <br />
            Sinamangal-9, Kathmandu, Nepal - 44600
          </p>
          <a href="">Phone: +9779801022970</a> <br />
          <a href="">email: rigelgirlshostel.np@gmail.com</a>
          <div class="py-5">
            <p>Follow Us on Social Media</p>
            <i class="fa-brands fa-square-facebook px-3 fa-2xl"></i>
            <i class="fa-brands fa-instagram fa-2xl"></i>
          </div>
        </div>
        <div class="form col-md-6">
          <div style="margin: 20px"></div>
         <form-comp/>
        </div>
      </div>
    </div>
  </template-view>
</template>

<script>
import FormComp from '@/components/FormComp.vue'
import TemplateView from "./TemplateView.vue";
export default {
  name: "ContactView",
  components: { TemplateView, FormComp },
};
</script>

<style scoped>
.address {
  background-image: url("https://static.wixstatic.com/media/20e5671799c242d8b8faf5edc41c7311.jpg/v1/fill/w_673,h_763,al_c,q_90,enc_auto/20e5671799c242d8b8faf5edc41c7311.jpg");
  object-fit: cover;
  height: 100vh;
  text-align: center;
}

a {
  text-decoration: none;
  color: black;
}
</style>