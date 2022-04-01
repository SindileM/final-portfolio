<template>
   <section id="about" class="about">
    <div class="about-me container">

      <div class="section-title">
        <h2>About</h2>
        <p>Learn more about me</p>
      </div>

      <div class="row">
        <div class="col-lg-4" data-aos="fade-right">
          <img src="https://i.postimg.cc/5yvv0jfZ/sindile-min.jpg" class="img-fluid" alt="">
        </div>
        <div class="col-lg-8 pt-4 pt-lg-0 content" data-aos="fade-left">
          <h3>UI/UX &amp; Web Developer</h3>
          <p class="fst-italic">
            Sindile is a 22 year old aspiring full stack developer from Cape Town, South Africa.
            I developed the love of he web from a young age and it just carried over into young adulthood..
          </p>
          <div class="row">
            <div class="col-lg-6">
              <ul class="fst-italic">
                <li><i class="fa fa-chevron-right"></i> <strong>Birthday:</strong> <span>03 December 1999</span></li>
                <li><i class="fa fa-chevron-right"></i> <strong>Phone:</strong> <span>+27 67 197 5655</span></li>
                <li><i class="fa fa-chevron-right"></i> <strong>City:</strong> <span>Cape Town,SA</span></li>
              </ul>
            </div>
            <div class="col-lg-6">
              <ul class="fst-italic">
                <li><i class="fa fa-chevron-right"></i> <strong>Age:</strong> <span>22</span></li>
                <li><i class="fa fa-chevron-right"></i> <strong>Email:</strong> <span>smakhathini24@gmail.com</span></li>
                <li><i class="fa fa-chevron-right"></i> <strong>Freelance:</strong> <span>Available</span></li>
              </ul>
            </div>
          </div>
          <p class="fst-italic">
            Officiis eligendi itaque labore et dolorum mollitia officiis optio vero. Quisquam sunt adipisci omnis et ut. Nulla accusantium dolor incidunt officia tempore. Et eius omnis.
            Cupiditate ut dicta maxime officiis quidem quia. Sed et consectetur qui quia repellendus itaque neque. Aliquid amet quidem ut quaerat cupiditate. Ab et eum qui repellendus omnis culpa magni laudantium dolores.
          </p>
        </div>
      </div>

    </div><!-- End About Me -->
    <div class="skills container">

      <div class="section-title">
        <h2>Skills</h2>
      </div>

      <div class="row skills-content">

        <div class="col-lg-6">

          <div class="progress">
            <span class="skill">HTML <i class="val">100%</i></span>
            <div class="progress-bar-wrap">
              <div class="progress-bar" role="progressbar" style="width: 100%" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100"></div>
            </div>
          </div>

          <div class="progress">
            <span class="skill">Mysql<i class="val">80%</i></span>
            <div class="progress-bar-wrap">
              <div class="progress-bar" role="progressbar" style="width: 80%" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100"></div>
            </div>
          </div>

          <div class="progress">
            <span class="skill">JavaScript <i class="val">50%</i></span>
            <div class="progress-bar-wrap">
              <div class="progress-bar" role="progressbar" style="width: 50%" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100"></div>
            </div>
          </div>

        </div>

        <div class="col-lg-6">

          <div class="progress">
            <span class="skill">Node <i class="val">70%</i></span>
            <div class="progress-bar-wrap">
              <div class="progress-bar" role="progressbar" style="width:70%" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100"></div>
            </div>
          </div>

          <div class="progress">
            <span class="skill">Vue js<i class="val">60%</i></span>
            <div class="progress-bar-wrap">
              <div class="progress-bar" role="progressbar" style="width:60%" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100"></div>
            </div>
          </div>

          <div class="progress">
            <span class="skill">Mongodb <i class="val">75%</i></span>
            <div class="progress-bar-wrap">
              <div class="progress-bar" role="progressbar" style="width:75%" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
            </div>
          </div>

        </div>

      </div>

    </div><!-- End Skills -->
</section>


</template>

<script>
export default {
    name:'About'
}
</script>
<style scoped>
.fst-italic{
    color: #fff;
}
    .about-me .content h3 {
  font-weight: 700;
  font-size: 26px;
  color: #18d26e;
}
.about-me .content ul {
  list-style: none;
  padding: 0;
}
.about-me .content ul li {
  margin-bottom: 20px;
  display: flex;
  align-items: center;
}
.about-me .content ul strong {
  margin-right: 10px;
}
.about-me .content ul i {
  font-size: 16px;
  margin-right: 5px;
  color: #18d26e;
  line-height: 0;
}
.about-me .content p:last-child {
  margin-bottom: 0;
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
.skills .progress {
  height: 60px;
  display: block;
  background: none;
  border-radius: 0;
}
.skills .progress .skill {
  padding: 10px 0;
  margin: 0;
  text-transform: uppercase;
  display: block;
  font-weight: 600;
  font-family: "Poppins", sans-serif;
  color: #fff;
}
.skills .progress .skill .val {
  float: right;
  font-style: normal;
}
.skills .progress-bar-wrap {
  background: rgba(255, 255, 255, 0.2);
}
.skills .progress-bar {
  width: 1px;
  height: 10px;
  transition: 0.9s;
  background-color: #18d26e;
}
</style>