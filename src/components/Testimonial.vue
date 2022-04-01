<template>
<section id="testimonials" class="testimonials">
 <div class="testimonials container">

      <div class="section-title">
        <h2>Testimonials</h2>
      </div>

      <div class="testimonials-slider swiper" data-aos="fade-up" data-aos-delay="100">
        <div class="swiper-wrapper">

          <div class="swiper-slide">
            <div class="testimonial-item">
              <p>
                <i class="bx bxs-quote-alt-left quote-icon-left"></i>
                {{testimonials.text}}
                <i class="bx bxs-quote-alt-right quote-icon-right"></i>
              </p>
              <img src="assets/img/testimonials/testimonials-1.jpg" class="testimonial-img" alt="">
              <h3>{{testimonials.name}}</h3>
              <h4> {{testimonials.title}}</h4>
            </div>
          </div><!-- End testimonial item -->
        </div>
        <div class="swiper-pagination"></div>
      </div>

      <div class="owl-carousel testimonials-carousel">

      </div>

    </div><!-- End Testimonials  -->

  </section>
</template>
<script>
export default {
    data(){
        return{
            testimonials:[]
        }
    },
    mounted(){
        fetch('https://sindile-portfolio.herokuapp.com/projects')
        .then(res => res.json())
        .then(data =>{
            this.testimonial = data
            console.log(testimonials);
        })
        .catch(err => console.log(err.message))
    },
name:'testimonials',
components:{

}
}
</script>
<style scoped>
.testimonials .testimonials-carousel, .testimonials .testimonials-slider {
  overflow: hidden;
}
.testimonials .testimonial-item {
  box-sizing: content-box;
  min-height: 320px;
}
.testimonials .testimonial-item .testimonial-img {
  width: 90px;
  border-radius: 50%;
  margin: -40px 0 0 40px;
  position: relative;
  z-index: 2;
  border: 6px solid rgba(255, 255, 255, 0.12);
}
.testimonials .testimonial-item h3 {
  font-size: 18px;
  font-weight: bold;
  margin: 10px 0 5px 45px;
  color: #111;
}
.testimonials .testimonial-item h4 {
  font-size: 14px;
  color: #111;
  margin: 0 0 0 45px;
}
.testimonials .testimonial-item .quote-icon-left, .testimonials .testimonial-item .quote-icon-right {
  color: rgba(255, 255, 255, 0.25);
  font-size: 26px;
}
.testimonials .testimonial-item .quote-icon-left {
  display: inline-block;
  left: -5px;
  position: relative;
}
.testimonials .testimonial-item .quote-icon-right {
  display: inline-block;
  right: -5px;
  position: relative;
  top: 10px;
}
.testimonials .testimonial-item p {
  font-style: italic;
  margin: 0 15px 0 15px;
  padding: 20px 20px 60px 20px;
  background: rgba(255, 255, 255, 0.1);
  position: relative;
  border-radius: 6px;
  position: relative;
  z-index: 1;
}
.testimonials .swiper-pagination {
  margin-top: 20px;
  position: relative;
}
.testimonials .swiper-pagination .swiper-pagination-bullet {
  width: 12px;
  height: 12px;
  opacity: 1;
  background-color: rgba(255, 255, 255, 0.3);
}
.testimonials .swiper-pagination .swiper-pagination-bullet-active {
  background-color: #18d26e;
}
section {
  /* overflow: hidden;
  position: absolute;
  width: 100%;
  top: 140px;
  bottom: 100%;
  opacity: 0; */
  transition: ease-in-out 0.4s;
  /* z-index: 2; */
}
section.section-show {
  top: 100px;
  bottom: auto;
  opacity: 1;
  padding-bottom: 45px;
}
section .container {
  background:#fff;
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
  color: #fff;
}
   
</style>