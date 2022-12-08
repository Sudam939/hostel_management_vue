<template>
  <template-view>
    <div class="title d-flex justify-content-center align-items-center">
      <h2>Services</h2>
    </div>

    <!-- Rooms -->
  <div class="py-5">
      <div class="container">
      <div class="row">
        <div class="col-md-7 py-5">
          <div class="container">
            <h2>Rooms</h2>
            <div class="row py-3 pb-5 text-muted">
              <div class="col-md-6">
                <li>Room 1 - 4 Seater</li>
                <li>Room 1 - 4 Seater</li>
                <li>Room 1 - 4 Seater</li>
                <li>Room 1 - 4 Seater</li>
              </div>
              <div class="col-md-6">
                <li>Room 1 - 4 Seater</li>
                <li>Room 1 - 4 Seater</li>
                <li>Room 1 - 4 Seater</li>
                <li>Room 1 - 4 Seater</li>
              </div>
            </div>
            <div class="text-muted">
              <li>Shared room of various size</li>
              <li>Shared room of various size</li>
              <li>Shared room of various size</li>
              <li>Shared room of various size</li>
            </div>
          </div>
        </div>
        <div class="col-md-5">
          <img
            src="https://static.wixstatic.com/media/bddef3_2b92668985a745ffb55f09f12eab71e1~mv2.jpg/v1/fill/w_579,h_821,al_c,q_90,enc_auto/bddef3_2b92668985a745ffb55f09f12eab71e1~mv2.jpg"
            alt=""
            height="500px"
            width="500px"
          />
        </div>
      </div>
    </div>
  </div>

    <!-- Meal -->
    <div class="meal container-fluid">
      <h2 class="py-5">Meals</h2>
      <li>Breakfast 7:00am - 8:00 am</li>
      <li>Breakfast 7:00am - 8:00 am</li>
      <li>Breakfast 7:00am - 8:00 am</li>
      <li>Breakfast 7:00am - 8:00 am</li>
      <p class="py-5">
        Fresh meals prepared everyday . <br /><br />
        Items on the menu may be changed according to available seasonal
        vegetables in the market. <br /><br />
        Timings can change during holidays, festivals and during different
        seasons.
      </p>
      <div class="container py-5">
        <div class="row">
          <div class="col-md-4"></div>
          <div class="col-md-4">
            <div class="border border-top border-bottom border-2 text-muted">
              <h2>View Our Menu</h2>
              <hr />
              <div style="display: flex; text-align: center; justify-content:center" >
                <h3 class="px-4 border-end">Week 1</h3>
                <h3 class="px-4">Week 2</h3>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Facilities -->
    <div class="title d-flex justify-content-center align-items-center">
      <h2>Others</h2>
    </div>
    <div class="other py-5">
      <div class="container-fluid">
        <div class="row">
          <div
            class="col-md-4 p-5"
            style="background-color: #6c757d;"
          >
            <i class="fa-solid fa-wifi fa-2xl py-4"></i>
            <h3>Wi-Fi</h3>
            <p>
              We provide semi official SME package which is a 35 mbps dedicated
              fiber line.
            </p>
          </div>
          <div class="col-md-4 p-5" style="color: black">
            <i class="fa-solid fa-shower fa-2xl py-4"></i>
            <h3>Shower</h3>
            <p>
              We have installed two 400L solar heater for hot water. We also
              electrically heat water during winter season.
            </p>
          </div>
          <div
            class="col-md-4 p-5"
            style="background-color: #bc9979; "
          >
            <i class="fa-solid fa-shield-halved fa-2xl py-4"></i>
            <h3>Security</h3>
            <p>
              We have a lady security guard patrolling the entire premises
              overnight.
            </p>
          </div>
        </div>
      </div>
      <div class="container-fluid">
        <div class="row">
          <div class="col-md-4 p-5" style="color: black">
            <i class="fa-solid fa-square-parking fa-2xl py-4"></i>
            <h3>Parking</h3>
            <p>
              Parking We have plenty of room for parking your personal scooters
              and bicycles.
            </p>
          </div>
          <div
            class="col-md-4 p-5"
            style="background-color: rgb(195, 144, 57); "
          >
            <i class="fa-solid fa-bed fa-2xl py-4"></i>
            <h3>Linen & Bedding</h3>
            <p>We provide all bedding and linen for your convenience.</p>
          </div>

          <div class="col-md-4 p-5" style="color: black">
            <i class="fa-regular fa-calendar-days fa-2xl py-4"></i>
            <h3>Events</h3>
            <p>
              Events We often like to organize events on various festivals, host
              movie nights and much more.
            </p>
          </div>
        </div>
      </div>
      <div class="container-fluid">
        <div class="row">
          <div
            class="col-md-4 p-5"
            style="background-color: #6c757d; "
          >
            <i class="fa-solid fa-tv fa-2xl py-4"></i>
            <h3>Television</h3>
            <p>
              Our television is located in the common dining area for you to
              enjoy.
            </p>
          </div>
          <div class="col-md-4 p-5" style="color: black">
            <i class="fa-solid fa-sink fa-2xl py-4"></i>
            <h3>Washing Machine</h3>
            <p>
              We have three washing machines for you to do your personal laundry
              and save time.
            </p>
          </div>
          <div
            class="col-md-4 p-5"
            style="background-color: #bc9979; "
          >
            <i class="fa-solid fa-gift fa-2xl py-4"></i>
            <h3>Offers & Rewards</h3>
            <p>
              Be a part of our hostel to enjoy exclusive offers and rewards we
              have in store for you.
            </p>
          </div>
        </div>
      </div>
    </div>
  </template-view>
</template>

<script>
import TemplateView from "./TemplateView.vue";
export default {
  name: "ServiceView",
  components: { TemplateView },
};
</script>

<style scoped>
img {
  object-fit: cover;
}

li {
  font-family: cinzel;
  font-size: 20px;
  font-weight: 15px;
}

.meal {
  text-align: center;
  background-image: url("https://th.bing.com/th/id/OIP.RulEbLLc9I3myhjBE2NlbwHaG4?w=165&h=180&c=7&r=0&o=5&dpr=1.3&pid=1.7");
}
.other {
  text-align: center;
  color: white;
}
</style>