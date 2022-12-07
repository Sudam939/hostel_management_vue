<template>
  <template-view>
    <div class="conatiner">
     <div class="row">
      <div class="col-md-2"></div>
      <div class="col-md-8">
         <div
        id="carouselExampleIndicators"
        class="carousel slide"
        data-bs-ride="true"
        style="height:100vh;background-color:#bc9979"
      >
        <div class="carousel-indicators">
          <button
            type="button"
            data-bs-target="#carouselExampleIndicators"
            data-bs-slide-to="0"
            class="active"
            aria-label="Slide 1"
          ></button>
          <button
            type="button"
            data-bs-target="#carouselExampleIndicators"
            data-bs-slide-to="1"
          ></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active py-3 m-3">
           <h1>Application Form</h1>
           
          </div>
          <div class="carousel-item py-3 m-3">
           <h1>Personal Info</h1>
          </div>
        </div>
        <button
          class="carousel-control-prev"
          type="button"
          data-bs-target="#carouselExampleIndicators"
          data-bs-slide="prev"
        >
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button
          class="carousel-control-next"
          type="button"
          data-bs-target="#carouselExampleIndicators"
          data-bs-slide="next"
        >
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
      </div>
      <div class="col-md-2"></div>
     </div>
    </div>
  </template-view>
</template>

<script>
import TemplateView from "./TemplateView.vue";
export default {
  name: "ApplicationformView",
  components: { TemplateView },
};
</script>

<style scoped>
h1{
  text-align: center;
}
</style>