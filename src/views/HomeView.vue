<template>
  <template-view>
    <!-- image -->
    <div class="carousel">
      <el-carousel indicator-position="outside" height="600px">
        <el-carousel-item v-for="item in 4" :key="item" style="maxHeight:600px">
          <img
            src="https://th.bing.com/th/id/R.a102f8b94f1d07ee628cd8a82bf0fe50?rik=IJ3FApi3KjOf3Q&riu=http%3a%2f%2fyouthhostel.html.themeplayers.net%2fonepager%2fassets%2fimages%2fdemo-content%2fhostel-3.jpg&ehk=vOlfF%2fM1dvws94AkZ5HBs9joKOCUGaALbzZiOasIXXo%3d&risl=&pid=ImgRaw&r=0"
            alt="" class="w-100 img-fluid" style="height:100%; objectFit:cover"
          />
        </el-carousel-item>
      </el-carousel>
    </div>

    <!-- about us -->
   <div class="py-5">
     <div class="container">
      <div class="row">
        <div class="col-md-6 py-5">
          <h2>About Us</h2>

          <p>
            The accommodation market in Kathmandu is highly saturated yet
            expensive for individual living. We are here to bring you a space
            that is affordable combined with simplicity and quality. We believe
            in strong community building and share a social responsibility
            towards the society. Women wanting to live, study or work in
            Kathmandu can find a safe and affordable place to stay while
            pursuing their dreams. <br />
            We offer a place where you get freedom to live individually and grow
            to become responsible adults. We would love to be a part of your
            wonderful life journey. We aspire to be an integral part and make a
            difference in the lives of the future generation. Our aim is to set
            a benchmark for the basic quality of living standards in hostels for
            students in Kathmandu. To achieve this we have carefully designed
            spaces to cater to the basic need for comfort of our residents.
          </p>
        </div>
        <div class="col-md-6">
          <img
            src="https://static.wixstatic.com/media/bddef3_586008cfb61f4d29909204e4b1813a53~mv2.jpg/v1/fill/w_644,h_740,al_c,q_90,enc_auto/bddef3_586008cfb61f4d29909204e4b1813a53~mv2.jpg"
            alt=""
          />
        </div>
      </div>
    </div>
   </div>

    <!-- faciities -->
    <div class="title d-flex justify-content-center align-items-center">
      <h2>Facilities</h2>
    </div>
    <div class="bg-light">
       <div class="container py-5">
      <div class="facilities row">
        <div class="col-md-4 py-3">
          <i class="fa-solid fa-bed fa-2xl py-3"></i>
          <h3>Rooms</h3>
          <p>
            Well designed shared rooms of various sizes with personal cupboards.
          </p>
        </div>
        <div class="col-md-4 py-3">
          <i class="fa-solid fa-plate-wheat fa-2xl py-3"></i>
          <h3>Meals</h3>
          <p>
            Well designed shared rooms of various sizes with personal cupboards.
          </p>
        </div>
        <div class="col-md-4 py-3">
          <i class="fa-solid fa-wifi fa-2xl py-3"></i>
          <h3>Wi-Fi</h3>
          <p>
            Well designed shared rooms of various sizes with personal cupboards.
          </p>
        </div>
        <div class="col-md-4 py-3">
          <i class="fa-solid fa-shower fa-2xl py-3"></i>
          <h3>Shower</h3>
          <p>
            Well designed shared rooms of various sizes with personal cupboards.
          </p>
        </div>
        <div class="col-md-4 py-3">
          <i class="fa-solid fa-shield-halved fa-2xl py-3"></i>
          <h3>Security</h3>
          <p>
            Well designed shared rooms of various sizes with personal cupboards.
          </p>
        </div>
        <div class="col-md-4 py-3">
          <i class="fa-solid fa-maximize fa-2xl py-3"></i>
          <h3>More</h3>
          <p>
            Well designed shared rooms of various sizes with personal cupboards.
          </p>
        </div>
      </div>
    </div>
    </div>

    <!-- booking -->
    <div class="py-5">
      <div class="container">
      <div class="row">
        <div class="col-md-3">
          <img
            src="https://static.wixstatic.com/media/bddef3_d79aa07cf6164fe6b107ac1994e1d703~mv2.jpg/v1/fill/w_336,h_426,al_c,q_90,enc_auto/bddef3_d79aa07cf6164fe6b107ac1994e1d703~mv2.jpg"
            class="img-fluid"
            height="340px"
            style="width: 100%"
          />
        </div>
        <div class="col-md-3">
          <div class="text-center py-3"><h1>Book Now</h1></div>
          <div class="text-center mb-5">
            Booking at your fingertips. We provide the quality and let you
            decide on the value.
          </div>
          <div class="d-flex justify-content-center">
            <button class="btn" @click="$router.push({ name: 'admission' })">
              Learn More
            </button>
          </div>
        </div>
        <div class="col-md-3">
          <img
            src="https://static.wixstatic.com/media/bddef3_d79aa07cf6164fe6b107ac1994e1d703~mv2.jpg/v1/fill/w_336,h_426,al_c,q_90,enc_auto/bddef3_d79aa07cf6164fe6b107ac1994e1d703~mv2.jpg"
            height="340px"
            class="img-fluid"
          />
        </div>
        <div class="col-md-3">
          <div class="text-center py-3"><h1>Book Now</h1></div>
          <div class="text-center mb-5">
            Booking at your fingertips. We provide the quality and let you
            decide on the value.
          </div>
          <div class="d-flex justify-content-center">
            <button class="btn" @click="$router.push({ name: 'admission' })">
              Learn More
            </button>
          </div>
        </div>
      </div>
    </div>
    </div>
  </template-view>
</template>

<script>
import TemplateView from "./TemplateView.vue";
export default {
  components: { TemplateView },
};
</script>

<style scoped>
.facility {
  color: white;
  background: var(--themeColor);
  height: 60px;
  text-align: center;
}
.btn {
  background: var(--themeColor);
  color: white;
}
</style>