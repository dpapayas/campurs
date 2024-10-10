<template>
  <NuxtLayout name="ygency" :header="3" :footer="5" :singlePage="true">
    <!-- Slider Section Start -->
    <SlidersHero5 />
    <!-- Slider Section End -->


    <!-- About Us Area start -->
    <section class="about-area-five py-130 rpy-100 rel z-1">
      <div class="container container-1290">
        <div class="row justify-content-between align-items-center">
          <div class="col-lg-6">
            <div class="about-content-five">
              <div class="section-title mb-40 wow fadeInUp delay-0-2s">
                <span class="sub-title mb-15">About Company</span>
                <h2>The World Class Digital Marketing Agency</h2>
              </div>
              <p>
                Sed ut perspiciatis unde omnis iste natus error voluptatem
                accusantium doloremque laudantium, totam reme aperiam eaque quae
                abillo inventorey veritatis quasi architecto beatae vitae dicta
                sunt explicabo.
              </p>
              
            </div>
          </div>
          <div class="col-xl-5 col-lg-6">
            <div class="about-five-images rmt-50 wow fadeInRight delay-0-2s">
              <div class="image-one">
                <img
                  src="/assets/images/campur/asset2.jpg"
                  alt="About Image"
                />
              </div>
              
              <div class="image-two mt-30">
                <img
                   src="/assets/images/campur/asset2.jpg"
                  alt="About Image"
                />
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- About Us Area end -->

    <!-- Work Gallery Area start -->
    <SlidersProject2 />
    <!-- Work Gallery Area end -->

    <!-- Counter Five start -->
    <div class="counter-section-five pb-80 rpb-50">
      <div class="container container-1290">
        <div class="row">
          <div class="col-xl-4 col-md-6">
            <div
              class="counter-item-three style-two counter-text-wrap wow fadeInRight delay-0-2s"
            >
              <i class="flaticon-software-development"></i>
              <span class="count-text plus" data-speed="3000" data-stop="15"
                >0</span
              >
              <span class="counter-title">Years Of Experience</span>
            </div>
          </div>
          <div class="col-xl-4 col-md-6">
            <div
              class="counter-item-three style-two counter-text-wrap wow fadeInRight delay-0-4s"
            >
              <i class="flaticon-development"></i>
              <span class="count-text plus" data-speed="3000" data-stop="63"
                >0</span
              >
              <span class="counter-title">Project Complete</span>
            </div>
          </div>
          <div class="col-xl-4 col-md-6">
            <div
              class="counter-item-three style-two counter-text-wrap wow fadeInRight delay-0-6s"
            >
              <i class="flaticon-branding"></i>
              <span class="count-text percent" data-speed="3000" data-stop="98"
                >0</span
              >
              <span class="counter-title">Clients Satisfactions</span>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- Counter Five end -->

    <!-- Video Area start -->
    <div class="video-area-five rel z-1">
      <div class="container container-1290">
        <div class="video-part style-three wow fadeInUp delay-0-2s">
          <img src="/assets/images/campur/asset3.png" alt="Video" />
          <a
            href="https://www.youtube.com/watch?v=9lzx1t9a96E"
            class="mfp-iframe video-play"
            ><i class="fas fa-play"></i
          ></a>
        </div>
      </div>
    </div>
    <!-- Video Area end -->
     
    <!-- Work With Us Area start -->
    <section class="work-with-us-area rel z-1">
      <div class="container container-1290">
        <div class="row no-gap">
          <div class="col-xl-5 align-self-center">
            <div class="work-with-image wow fadeInUp delay-0-2s">
              <img src="/assets/images/campur/asset7.jpg" alt="About" />
            </div>
          </div>
          <div class="col-xl-7 wow fadeInUp delay-0-4s">
            <div
              class="work-with-content"
              style="
                background-image: url(assets/images/about/work-with-us-bg.jpg);
              "
            >
              <div class="section-title mb-10">
                <span class="sub-title mb-15">Work With Us</span>
                <h2>Ada acara yang ingin diadakan! Hubungi Kami</h2>
              </div>
              
              <NuxtLink href="contact" class="theme-btn mt-15"
                >Kontak Kami <i class="far fa-arrow-right"></i
              ></NuxtLink>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Work With Us Area end -->
  </NuxtLayout>
</template>

<script>
import { ygencyUtilits } from "~/utilits";

export default {
  name: "index5",
  mounted() {
    ygencyUtilits.counterUp();
  },
};
</script>
