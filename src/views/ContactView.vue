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
        <div class="py-5">
          <h2>Find Us on Google Maps</h2>
          <iframe
            src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d28485.296991022653!2d87.286299!3d26.818885!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x9b8526c7c4c7bc1c!2sCode%20IT!5e0!3m2!1sen!2snp!4v1669877658010!5m2!1sen!2snp"
            style="border: 0;height:100vh;width:100%"
            allowfullscreen=""
            loading="lazy"
            referrerpolicy="no-referrer-when-downgrade"
          ></iframe>
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
h2{
  text-align: center;
}

a {
  text-decoration: none;
  color: black;
}
</style>