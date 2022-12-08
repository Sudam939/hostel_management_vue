<template>
  <div class="footer py-5">
    <div class="container">
      <div class="row">
        <div class="col-md-4">
          <h1>Direction</h1>
          <iframe
            src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d28485.296991022653!2d87.286299!3d26.818885!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x9b8526c7c4c7bc1c!2sCode%20IT!5e0!3m2!1sen!2snp!4v1669877658010!5m2!1sen!2snp"
            style="border: 0"
            allowfullscreen=""
            loading="lazy"
            referrerpolicy="no-referrer-when-downgrade"
          ></iframe>
        </div>
        <div class="col-md-4">
          <h1>Visit Us</h1>
          <p>
            Operation Hours <br />
            Sunday - Friday 10am to 6pm Saturday - Make an appointment <br />
            <br />
            20 Pashupati Marg, Bhimsengola, Sinamangal, Kathmandu, Nepal
          </p>
        </div>
        <div class="col-md-4">
          <h1>Get in Touch</h1>
          <div>
            <a href="">Phone: +9779801022970</a> <br />
            <a href="">email: rigelgirlshostel.np@gmail.com</a>
          </div>
          <div class="py-5">
            <h3>Message Us</h3>
            <p>Follow Us on Social Media</p>
            <i class="fa-brands fa-square-facebook px-3 fa-2xl"></i>
            <i class="fa-brands fa-instagram fa-2xl"></i>
          </div>
        </div>
      </div>
    </div>
    <div>
        <form class="form" action="">
            <div class="mb-3">
              <input
                type="email"
                class="form-control"
                id="exampleInputEmail1"
                aria-describedby="emailHelp"
                placeholder="Enter your email address"
              />
              <p>We'll never share your email with anyone else.</p>
            </div>
             <button class="btn border-radius:2px bg-white text-muted">Join</button>
          </form>
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterComp",
};
</script>

<style scoped>
.footer{
  color: white;
  background: var(--themeColor);
}
a {
  text-decoration: none;
  color: white;
}
.form{
    display: flex;
    justify-content: center;
    text-align: center;
    
}
.btn{
    height: 38px;
}
</style>