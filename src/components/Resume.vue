<template >
      <!-- ======= Resume Section ======= -->
  <section id="resume" class="resume">
    <div class="container">

      <div class="section-title">
        <h2>Resume</h2>
        <p>Check My Resume</p>
      </div>

      <div class="row">
        <div class="col-lg-6">
          <h3 class="resume-title">Sumary</h3>
          <div class="resume-item pb-0">
            <h4>Sindile Makhathini</h4>
            <p><em>Sindile is a 22 year old aspiring full stack developer from Cape Town, South Africa.I developed the love of the web from a young age and it just carried over into young adulthood.</em></p>
            <!-- <p>
            <ul>
              <li>Cape Town, South Africa</li>
              <li>+27 67 197 5655</li>
            </ul>
            </p> -->
          </div>

          <h3 class="resume-title">Education</h3>
          <div class="resume-item">
            <h4>NATIONAL SENIOR CERTIFICATE</h4>
            <h5>2013</h5>
            <p><em>Malibu Secondary School</em></p>
            <p>MATHS <br> 
                PHYSICAL SCIENCE<br> 
                LIFE SCIENCES <br> 
                GEOGRAPHY <br> 
                ENGLISH HOME LANGUAGE <br>
                AFRIKAANS FIRST ADDITIONAL LANGUAGE <br> 
                LIFE ORIENTATION <br> 
               </p> 
          </div>
          <div class="resume-item">
            <h4>Fullstack Developer</h4>
            <h5>2021-present</h5>
            <p><em>Lifechoices Coding Academy</em></p>
            <p>HTML5 <br>
                CSS  <br>
                BOOTSTRAP <br>
                MYSQL <br>
                JAVASCRIPT <br>
                NODE JS <br>
                VUE JS <br>
            </p>
          </div>
        </div>
        <div class="col-lg-6">
          <h3 class="resume-title">Professional Experience</h3>
          <div class="resume-item">
            <h4>ETHEMBENI EDUCARE CENTRE</h4>
            <h5>2018</h5>
            <p><em>Volunteering</em></p>
            <p>
                I took a gap year to find what I wanted to do with my life while also volunteerig at the local orphange.
            </p>
          </div>
          <div class="resume-item">
            <h4>CLOUDWORKERS</h4>
            <h5>2019</h5>
            <p><em>Online customer service moderator</em></p>
            <p>
        Working as an online customer service moderator gave me the skills I needed to connect with people online.
            </p>
          </div>
          <div class="resume-item">
            <h4>REV TRANSCRIPTION AND WORK AND EDUCATION</h4>
            <h5>2020</h5>
            <p><em>Transcriber</em></p>
            <p>
                I worked as a transcriber for Rev. An online company that turns audio into written text. 
                It taught me good listening skills as well following instructions
            </p>
          </div>
        </div>
      </div>

    </div>
  </section><!-- End Resume Section -->
</template>
<script>
export default {
    
}
</script>
<style>
    .resume .resume-title {
  font-size: 26px;
  font-weight: 700;
  margin-top: 20px;
  margin-bottom: 20px;
  color: #111;
}
.resume .resume-item {
  padding: 0 0 20px 20px;
  margin-top: -2px;
  border-left: 2px solid rgba(255, 255, 255, 0.2);
  position: relative;
}
.resume .resume-item h4 {
  line-height: 18px;
  font-size: 18px;
  font-weight: 600;
  text-transform: uppercase;
  font-family: "Poppins", sans-serif;
  color: #18d26e;
  margin-bottom: 10px;
}
.resume .resume-item h5 {
  font-size: 16px;
  background: rgba(255, 255, 255, 0.15);
  padding: 5px 15px;
  display: inline-block;
  font-weight: 600;
  margin-bottom: 10px;
}
.resume .resume-item ul {
  padding-left: 20px;
}
.resume .resume-item ul li {
  padding-bottom: 10px;
}
.resume .resume-item:last-child {
  padding-bottom: 0;
}
.resume .resume-item::before {
  content: "";
  position: absolute;
  width: 16px;
  height: 16px;
  border-radius: 50px;
  left: -9px;
  top: 0;
  background: #18d26e;
  border: 2px solid #18d26e;
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
  /* background: rgba(0, 0, 0, 0.9); */
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
  color: #111;
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
  color: #111;
}
</style>