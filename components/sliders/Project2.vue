<template>
  <section class="work-gallery-area py-130 rpy-100">
    <div class="container container-1290">
      <div class="row justify-content-center">
        <div class="col-xl-8 col-lg-10">
          <div class="section-title text-center mb-60 wow fadeInUp delay-0-2s">
            <span class="sub-title mb-20">Gallery Acara</span>
            <h2>Gallery Cahyo Mudho</h2>
          </div>
        </div>
      </div>
    </div>
    <div class="container-fluid">
      <div class="gallery-five-active">
        <Swiper
          :modules="[SwiperAutoplay, SwiperNavigation, SwiperPagination]"
          :slides-per-view="1"
          :loop="true"
          :autoplay="{
            delay: 8000,
            disableOnInteraction: true,
          }"
          :navigation="{
            nextEl: '.work-gallery-next',
            prevEl: '.work-gallery-prev',
          }"
          :pagination="{
            el: '.p2-dot',
            clickable: true,
          }"
          :breakpoints="{
            640: {
              slidesPerView: 2,
              spaceBetween: 15,
            },
            768: {
              slidesPerView: 3,
              spaceBetween: 15,
            },
            1400: {
              slidesPerView: 4,
              spaceBetween: 15,
            },
          }"
        >
          <SwiperSlide class="project-item style-five wow fadeInUp delay-0-2s">
            <div class="image">
              <img
                src="/assets/images/campur/asset4.jpg"
                alt="Work Gallery"
              />
              <NuxtLink href="project-details" class="project-btn"
                ><i class="far fa-arrow-right"></i
              ></NuxtLink>
            </div>
            <div class="content">
              <NuxtLink href="projects" class="category"
                >Marketing, Branding</NuxtLink
              >
              <h4>
                <NuxtLink href="project-details"
                  >Social Media Marketing</NuxtLink
                >
              </h4>
            </div>
          </SwiperSlide>
          <SwiperSlide class="project-item style-five wow fadeInUp delay-0-4s">
            <div class="image">
              <img
                src="/assets/images/campur/asset5.jpg"
                alt="Work Gallery"
              />
              <NuxtLink href="project-details" class="project-btn"
                ><i class="far fa-arrow-right"></i
              ></NuxtLink>
            </div>
            <div class="content">
              <NuxtLink href="projects" class="category"
                >Marketing, Branding</NuxtLink
              >
              <h4>
                <NuxtLink href="project-details"
                  >Social Media Marketing</NuxtLink
                >
              </h4>
            </div>
          </SwiperSlide>
          <SwiperSlide class="project-item style-five wow fadeInUp delay-0-6s">
            <div class="image">
              <img
                src="/assets/images/campur/asset6.jpg"
                alt="Work Gallery"
              />
              <NuxtLink href="project-details" class="project-btn"
                ><i class="far fa-arrow-right"></i
              ></NuxtLink>
            </div>
            <div class="content">
              <NuxtLink href="projects" class="category"
                >Marketing, Branding</NuxtLink
              >
              <h4>
                <NuxtLink href="project-details"
                  >Social Media Marketing</NuxtLink
                >
              </h4>
            </div>
          </SwiperSlide>
          <SwiperSlide class="project-item style-five wow fadeInUp delay-0-8s">
            <div class="image">
              <img
                src="/assets/images/campur/asset6.jpg"
                alt="Work Gallery"
              />
              <NuxtLink href="project-details" class="project-btn"
                ><i class="far fa-arrow-right"></i
              ></NuxtLink>
            </div>
            <div class="content">
              <NuxtLink href="projects" class="category"
                >Marketing, Branding</NuxtLink
              >
              <h4>
                <NuxtLink href="project-details"
                  >Social Media Marketing</NuxtLink
                >
              </h4>
            </div>
          </SwiperSlide>
          <SwiperSlide class="project-item style-five wow fadeInUp delay-0-2s">
            <div class="image">
              <img
                src="/assets/images/campur/asset6.jpg"
                alt="Work Gallery"
              />
              <NuxtLink href="project-details" class="project-btn"
                ><i class="far fa-arrow-right"></i
              ></NuxtLink>
            </div>
            <div class="content">
              <NuxtLink href="projects" class="category"
                >Marketing, Branding</NuxtLink
              >
              <h4>
                <NuxtLink href="project-details"
                  >Social Media Marketing</NuxtLink
                >
              </h4>
            </div>
          </SwiperSlide>
          <SwiperSlide class="project-item style-five wow fadeInUp delay-0-2s">
            <div class="image">
              <img
                src="/assets/images/campur/asset6.jpg"
                alt="Work Gallery"
              />
              <NuxtLink href="project-details" class="project-btn"
                ><i class="far fa-arrow-right"></i
              ></NuxtLink>
            </div>
            <div class="content">
              <NuxtLink href="projects" class="category"
                >Marketing, Branding</NuxtLink
              >
              <h4>
                <NuxtLink href="project-details"
                  >Social Media Marketing</NuxtLink
                >
              </h4>
            </div>
          </SwiperSlide>
          <SwiperSlide class="project-item style-five wow fadeInUp delay-0-2s">
            <div class="image">
              <img
                src="/assets/images/campur/asset5.jpg"
                alt="Work Gallery"
              />
              <NuxtLink href="project-details" class="project-btn"
                ><i class="far fa-arrow-right"></i
              ></NuxtLink>
            </div>
            <div class="content">
              <NuxtLink href="projects" class="category"
                >Marketing, Branding</NuxtLink
              >
              <h4>
                <NuxtLink href="project-details"
                  >Social Media Marketing</NuxtLink
                >
              </h4>
            </div>
          </SwiperSlide>
          <SwiperSlide class="project-item style-five wow fadeInUp delay-0-2s">
            <div class="image">
              <img
                src="/assets/images/campur/asset4.jpg"
                alt="Work Gallery"
              />
              <NuxtLink href="project-details" class="project-btn"
                ><i class="far fa-arrow-right"></i
              ></NuxtLink>
            </div>
            <div class="content">
              <NuxtLink href="projects" class="category"
                >Marketing, Branding</NuxtLink
              >
              <h4>
                <NuxtLink href="project-details"
                  >Social Media Marketing</NuxtLink
                >
              </h4>
            </div>
          </SwiperSlide>
        </Swiper>
      </div>
      <div class="work-gallery-controls">
        <button class="work-gallery-prev slick-arrow">
          <i class="far fa-chevron-left"></i>
        </button>
        <div class="work-gallery-dots">
          <div class="slick-dots p2-dot"></div>
        </div>
        <button class="work-gallery-next slick-arrow">
          <i class="far fa-chevron-right"></i>
        </button>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Project2",
};
</script>
