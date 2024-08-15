<script setup lang="ts">
</script>

<template>
  <div class="site_contain">
    <div class="fix-bg">
      <div class="Ellipse1"></div>
      <div class="Ellipse2"></div>
      <button id="menu-toggle" class="menu-toggle-button">
                <span class="hamburger" id="hamburger-1">
                    <span class="line"></span>
                    <span class="line"></span>
                    <span class="line"></span>
                </span>
      </button>
      <div class="container">
        <!-- ====================================== Side Menu ===================================== -->
        <div class="side-menu">
          <div class="profile-img-main">
            <img class="zoom_in" alt="profile-img">
            <h1 class="fade_up">Jessica <span>Biogi</span></h1>
            <h2 class="designer fade_up">Web Developer</h2>
            <div class="profile-media-icons-main fade_up">
              <a href="mailto:hello@biogi.com" class="profile-media-icons">
                <img  alt="email-svg">
              </a>
              <a href="https://www.behance.net/" class="profile-media-icons">
                <img  alt="behance-svg">
              </a>
              <a href="https://dribbble.com/" class="profile-media-icons">
                <img  alt="drribale-svg">
              </a>
              <a href="https://medium.com/" class="profile-media-icons">
                <img alt="medium-svg">
              </a>
            </div>
          </div>
          <div class="menu-list-main">
            <ul>
              <li class="active-menu-action">
                <a class="fade_right" href="#home">
                  <img  alt="home-svg">Home
                </a>
              </li>
              <li class="active-menu-action">
                <a class="fade_right" href="#about">
                  <img alt="home-svg">About
                </a>
              </li>
              <li class="active-menu-action">
                <a class="fade_right" href="#resume">
                  <img alt="home-svg">Resume
                </a>
              </li>
              <li class="active-menu-action">
                <a class="fade_right" href="#services">
                  <img  alt="home-svg">Services
                </a>
              </li>
              <li class="active-menu-action">
                <a class="fade_right" href="#portfolio">
                  <img alt="home-svg">Portfolio
                </a>
              </li>
              <li class="active-menu-action">
                <a class="fade_right" href="#pricing">
                  <img  alt="home-svg">Pricing
                </a>
              </li>
              <li class="active-menu-action">
                <a class="fade_right" href="#blog">
                  <img  alt="home-svg">Blog
                </a>
              </li>
              <li class="active-menu-action" id="contact-line">
                <a class="fade_right" href="#contact">
                  <img  alt="home-svg">Contact
                </a>
              </li>
            </ul>
          </div>
          <div>
            <div id="wrap">
              <a href="assets/pdf/olivia_resume.pdf" class="btn-slide">
                                <span class="circle">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"
                                         fill="none">
                                        <path class="download-svg"
                                              d="M13 12H16L12 16L8 12H11V8H13V12ZM15 4H5V20H19V8H15V4ZM3 2.9918C3 2.44405 3.44749 2 3.9985 2H16L20.9997 7L21 20.9925C21 21.5489 20.5551 22 20.0066 22H3.9934C3.44476 22 3 21.5447 3 21.0082V2.9918Z"
                                              fill="white" />
                                    </svg>
                                </span>
                <span class="title">Download CV</span>
                <span class="title-hover">Click Here</span>
              </a>
            </div>
          </div>
        </div>
        <!-- ====================================== Side Menu End ===================================== -->
        <div class="main-containe" data-bs-spy="scroll">
          <!-- ====================================== Section One ===================================== -->
          <section class="section-one overflow-hidden" id="home">
            <div class="row">
              <div class="col-xxl-6 col-lg-6">
                <h2 class="jessica-main-text zoom_in">Jessica <span>Biogi</span></h2>
                <h3 class="back-End-dev designer2">Back-End Web Developer</h3>
                <p class="best fade_down">We appreciate your trust greatly our clients choose us & our
                  products because they know we are the best.</p>
                <div class="section-one-btns-main fade_down">
                  <div class="wrapper">
                    <a class="btn-hover" href="#">View Work</a>
                  </div>
                  <div class="wrapper">
                    <a class="btn-hover btn-hover2" href="#">Contact Me</a>
                  </div>
                </div>
              </div>
              <div class="col-xxl-6 col-lg-6 position-relative">
                <img class="flower"  alt="flower">
                <img class="circular-img"  alt="circular-img">
                <img class="jessica-main-img zoom_in"
                     alt="jessica-main-img">
                <div class="worked-box">
                  <p class="worked-more">Worked with more than 100 people</p>
                  <div class="client-img-main position-relative">
                    <img class="client-img client-img1"
                         alt="clients-img1">
                    <img class="client-img client-img2"
                         alt="clients-img2">
                    <img class="client-img client-img3"
                         alt="clients-img3">
                    <img class="client-img client-img4"
                         alt="clients-img4">
                    <p class="worked-more worked-more2"> 100+ Clients</p>
                  </div>
                </div>
              </div>
            </div>
          </section>
        </div>
      </div>
    </div>
  </div>
</template>

