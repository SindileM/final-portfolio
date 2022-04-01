<template>
 <section id="contact" class="contact">
    <div class="container">

      <div class="section-title">
        <h2>Contact</h2>
        <p>Contact Me</p>
      </div>

      <div class="row mt-2">
        <div class="col-md-6 mt-4 d-flex align-items-stretch">
          <div class="info-box">
            <i class="fa fa-envelope"></i>
            <h3>Email Me</h3>
            <p>smakhathini24@gmail.com</p>
          </div>
        </div>
        <div class="col-md-6 mt-4 d-flex align-items-stretch">
          <div class="info-box">
            <i class="fa fa-phone-call"></i>
            <h3>Call Me</h3>
            <p>+27 67 197 5655</p>
          </div>
        </div>
      </div>

      <form action="" method="post" role="form" class="php-email-form mt-4">
        <div class="row">
          <div class="col-md-6 form-group">
            <input type="text" name="name" class="form-control" id="name" placeholder="Your Name" required>
          </div>
          <div class="col-md-6 form-group mt-3 mt-md-0">
            <input type="email" class="form-control" name="email" id="email" placeholder="Your Email" required>
          </div>
        </div>
        <div class="form-group mt-3">
          <input type="text" class="form-control" name="subject" id="subject" placeholder="Subject" required>
        </div>
        <div class="form-group mt-3">
          <textarea class="form-control" name="message" rows="5" placeholder="Message" required></textarea>
        </div>
        <div class="text-center"><button type="submit">Send Message</button></div>
      </form>

    </div>
  </section>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .contact .info-box {
  color: #444444;
  padding: 20px;
  width: 100%;
  background: rgba(255, 255, 255, 0.08);
}
.contact .info-box i.fa {
  font-size: 24px;
  color: #18d26e;
  border-radius: 50%;
  padding: 14px;
  float: left;
  background: rgba(255, 255, 255, 0.1);
}
.contact .info-box h3 {
  font-size: 20px;
  color: #fff;
  font-weight: 700;
  margin: 10px 0 8px 68px;
}
.contact .info-box p {
  padding: 0;
  color: #fff;
  line-height: 24px;
  font-size: 14px;
  margin: 0 0 0 68px;
}

.contact .php-email-form {
  padding: 30px;
  background: rgba(255, 255, 255, 0.08);
}
.contact .php-email-form .error-message {
  display: none;
  background: rgba(255, 255, 255, 0.08);
  background: #ed3c0d;
  text-align: left;
  padding: 15px;
  font-weight: 600;
}
.contact .php-email-form .error-message br + br {
  margin-top: 25px;
}
.contact .php-email-form .sent-message {
  display: none;
  background: rgba(255, 255, 255, 0.08);
  background: #18d26e;
  text-align: center;
  padding: 15px;
  font-weight: 600;
}
.contact .php-email-form .loading {
  display: none;
  background: rgba(255, 255, 255, 0.08);
  text-align: center;
  padding: 15px;
}
.contact .php-email-form .loading:before {
  content: "";
  display: inline-block;
  border-radius: 50%;
  width: 24px;
  height: 24px;
  margin: 0 10px -6px 0;
  border: 3px solid #18d26e;
  border-top-color: #eee;
  -webkit-animation: animate-loading 1s linear infinite;
  animation: animate-loading 1s linear infinite;
}
.contact .php-email-form input, .contact .php-email-form textarea {
  border-radius: 0;
  box-shadow: none;
  font-size: 14px;
  background: rgba(255, 255, 255, 0.08);
  border: 0;
  transition: 0.3s;
  color: #fff;
}
.contact .php-email-form input:focus, .contact .php-email-form textarea:focus {
  background-color: #fff;
}
.contact .php-email-form input::-moz-placeholder, .contact .php-email-form textarea::-moz-placeholder {
  color: #fff;
  opacity: 1;
}
.contact .php-email-form input::placeholder, .contact .php-email-form textarea::placeholder {
  color: rgba(255, 255, 255, 0.3);
  opacity: 1;
}
.contact .php-email-form input {
  padding: 10px 15px;
}
.contact .php-email-form textarea {
  padding: 12px 15px;
}
.contact .php-email-form button[type=submit] {
  background: #18d26e;
  border: 0;
  padding: 10px 30px;
  color: #fff;
  transition: 0.4s;
  border-radius: 4px;
}
.contact .php-email-form button[type=submit]:hover {
  background: #15bb62;
}
@-webkit-keyframes animate-loading {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}
@keyframes animate-loading {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}

section {
  transition: ease-in-out 0.4s;
}
section.section-show {
  top: 100px;
  bottom: auto;
  opacity: 1;
  padding-bottom: 45px;
}
section .container {
  background: rgba(0, 0, 0, 0.9);
  padding: 30px;
}
@media (max-width: 768px) {
  section {
    top: 120px;
  }
  section.section-show {
    top: 80px;
  }
}

.section-title h2 {
  font-size: 14px;
  font-weight: 500;
  padding: 0;
  line-height: 1px;
  margin: 0 0 20px 0;
  letter-spacing: 2px;
  text-transform: uppercase;
  color: #fff;
  font-family: "Poppins", sans-serif;
}
.section-title h2::after {
  content: "";
  width: 120px;
  height: 1px;
  display: inline-block;
  background: #4ceb95;
  margin: 4px 10px;
}
.section-title p {
  margin: 0;
  margin: -15px 0 15px 0;
  font-size: 36px;
  font-weight: 700;
  text-transform: uppercase;
  font-family: "Poppins", sans-serif;
  color: #fff;
}
</style>