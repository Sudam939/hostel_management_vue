<template>
  <div class="container-fluid">
    <!-- Step-1 -->
    <div class="step text-muted py-5 ms-5">
      <h1>Step:1</h1>
      <h3>Check Availability</h3>
      <li class="p-3">
        Please choose a room and bed from our availability chart provided below
        Be advised that all rooms are shared.
      </li>
      <li class="p-3">All available toilets and showers are common.</li>
      <li class="p-3">
        There are two common rooms and outdoor space to relax and study, along
        with common dining room.
      </li>
      <li class="p-3">
        Individual lockable cupboards are provided for the safety of your
        belongings.
      </li>
    </div>

    <!-- Table -->
    <div class="container py-5">
      <table class="table border border-2 py-5">
        <thead>
          <tr>
            <th scope="col"></th>
            <th scope="col">Bed 1</th>
            <th scope="col">Bed 2</th>
            <th scope="col">Bed 3</th>
            <th scope="col">Bed 4</th>
            <th scope="col">Bed 5</th>
            <th scope="col">Bed 6</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th scope="row">Room 1 (4 Seater)</th>
            <td>Available</td>
            <td>Available</td>
            <td>Available</td>
            <td>N/A</td>
            <td>N/A</td>
            <td>N/A</td>
          </tr>
          <tr>
            <th scope="row">Room 1 (4 Seater)</th>
            <td>Available</td>
            <td>Available</td>
            <td>N/A</td>
            <td>N/A</td>
            <td>N/A</td>
            <td>X</td>
          </tr>
          <tr>
            <th scope="row">Room 1 (4 Seater)</th>
            <td>X</td>
            <td>Available</td>
            <td>Available</td>
            <td>Available</td>
            <td>X</td>
            <td>X</td>
          </tr>
          <tr>
            <th scope="row">Room 1 (4 Seater)</th>
            <td>X</td>
            <td>X</td>
            <td>Available</td>
            <td>Available</td>
            <td>N/A</td>
            <td>N/A</td>
          </tr>
          <tr>
            <th scope="row">Room 1 (4 Seater)</th>
            <td>Available</td>
            <td>Available</td>
            <td>N/A</td>
            <td>N/A</td>
            <td>X</td>
            <td>X</td>
          </tr>
          <tr>
            <th scope="row">Room 1 (4 Seater)</th>
            <td>N/A</td>
            <td>N/A</td>
            <td>Available</td>
            <td>Available</td>
            <td>Available</td>
            <td>Available</td>
          </tr>
          <tr>
            <th scope="row">Room 1 (4 Seater)</th>
            <td>Available</td>
            <td>Available</td>
            <td>Available</td>
            <td>X</td>
            <td>X</td>
            <td>X</td>
          </tr>
          <tr>
            <th scope="row">Room 1 (4 Seater)</th>
            <td>Available</td>
            <td>Available</td>
            <td>Available</td>
            <td>X</td>
            <td>N/A</td>
            <td>X</td>
          </tr>
        </tbody>
      </table>
      <div style="float: right">
        <p>
          N/A - Currently Occupied <br />
          Available - Currently Unoccupied <br />
          X - Beds Not Applicable
        </p>
      </div>
    </div>

    <!-- step-2 -->
    <div class="step text-muted py-5 ms-5">
      <h1>Step:2</h1>
      <h3>Check Prices</h3>
      <li class="p-3">
        Admission fee - It is a one off payment which need to be paid on signing
        the contract.
      </li>
      <li class="p-3">
        Booking fee - Payment made once booking has been approved. This amount
        will be deducted from your first month's fee
      </li>
      <li class="p-3">
        Monthly fee - Different for each room. Has to be paid by the 1st of
        every month of B.S. Calendar.
      </li>
      <li class="p-3">
        Security Deposit - Must be paid at the start of your stay. This will be
        refunded to you at the end of your stay. The amount is equivalent to
        your one month's fee.
      </li>

      <!-- table -->
       <table class="table border border-2 py-5">
        <thead>
          <tr>
            <th scope="col"></th>
            <th scope="col">Admission Fee</th>
            <th scope="col">Booking Fee</th>
            <th scope="col">Monthly Fee</th>
            <th scope="col">Security Deposit</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th scope="row">Room 1</th>
            <td>3000</td>
            <td>3000</td>
            <td>18000</td>
            <td>18000</td>
          </tr>
          <tr>
            <th scope="row">Room 2</th>
            <td>3000</td>
            <td>3000</td>
            <td>18000</td>
            <td>18000</td>
          </tr>
          <tr>
            <th scope="row">Room 3</th>
            <td>3000</td>
            <td>3000</td>
            <td>18000</td>
            <td>18000</td>
          </tr>
          <tr>
            <th scope="row">Room 4</th>
            <td>3000</td>
            <td>3000</td>
            <td>18000</td>
            <td>18000</td>
          </tr>
          <tr>
            <th scope="row">Room 5</th>
            <td>3000</td>
            <td>3000</td>
            <td>18000</td>
            <td>18000</td>
          </tr>
          <tr>
            <th scope="row">Room 6</th>
            <td>3000</td>
            <td>3000</td>
            <td>18000</td>
            <td>18000</td>
          </tr>
          <tr>
            <th scope="row">Room 7</th>
            <td>3000</td>
            <td>3000</td>
            <td>18000</td>
            <td>18000</td>
          </tr>
          <tr>
            <th scope="row">Room 8</th>
            <td>3000</td>
            <td>3000</td>
            <td>18000</td>
            <td>18000</td>
          </tr>
        </tbody>
      </table>
    </div>

    <!-- step-3 -->
    <div class="step text-muted py-5 ms-5">
      <h1>Step:3</h1>
      <h3>Application Form</h3>
      <li class="p-3">
        Now that you have selected your room and bed. Please note down the room and bed number as you will need it to fill up the application form.
      </li>
      <li class="p-3">Once you have submitted the form, our team will get in touch with you to finalize your booking.
     </li>
      <li class="p-3">
        Please click on the link below to fill up the form and submit it to us.
      </li>
     <button @click="modalView()" class="btn">Application Form</button>
    </div>
     <modal name="applicationForm">
    <div class="py-5">
      <form action="submit"                   >
        <div class="container">
          <h3>Application Form</h3>
          <div class="row">
            <div class="col-md-6">
              <div class="mb-3">
                <label class="form-label">Full Name</label>
                <input
                  type="text"
                  class="form-control"
                  placeholder="Write your name here"
                />
              </div>
              <div class="mb-3">
                <label class="form-label">Email</label>
                <input
                  type="email"
                  class="form-control"
                  placeholder="Write your email here"
                />
              </div>
            </div>
             <div class="col-md-6">
              <div class="mb-3">
                <label class="form-label">Last Name</label>
                <input
                  type="text"
                  class="form-control"
                  placeholder="Write your name here"
                />
              </div>
              <div class="mb-3">
                <label class="form-label">Room/Bed No*</label>
                <input
                  type="email"
                  class="form-control"
                  placeholder="Write your email here"
                />
              </div>
            </div>
          </div>
        </div>
      </form>
    </div>
  </modal>
  </div>
  
</template>

<script>
export default {
  name: "InfoComp",
  
  methods:{
        modalView(){
        this.$modal.show("applicationForm");
    }
  }
};
</script>

<style scoped>
.container-fluid {
  text-align: center;
}

p {
  font-family: itali;
  font-size: 14px;
}

h3 {
  justify-content: center;
  align-items: center;
  text-align: center;
}

.btn{
  background: var(--themeColor);
  color: white;
}

</style>