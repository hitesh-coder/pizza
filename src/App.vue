<template>
  <div id="app">
    <section class="first-section">
      <h1>Make Your Site Move with <br />Animation</h1>
      <div class="images-wrapper">
        <img class="section_1_bg" src="./assets/img/section_1_bg.webp" />
        <div class="ingredient-images">
          <img class="section_1_01" src="./assets/img/section_1_01.webp" />
          <img class="section_1_02" src="./assets/img/section_1_02.webp" />
          <img class="section_1_03" src="./assets/img/section_1_03.webp" />
          <img class="section_1_04" src="./assets/img/section_1_04.webp" />
          <img class="section_1_05" src="./assets/img/section_1_05.webp" />
          <img class="section_1_06" src="./assets/img/section_1_06.webp" />
          <img class="section_1_07" src="./assets/img/section_1_07.webp" />
          <img class="section_1_08" src="./assets/img/section_1_08.webp" />
          <img class="section_1_09" src="./assets/img/section_1_09.webp" />
        </div>
      </div>
    </section>
    <section class="second-section">
      <h1>Draw Attention Where You Want it Most</h1>
      <p>A great animation effect is impossible to ignore.</p>
      <div class="images-wrapper bottom">
        <div class="image-container">
          <img class="section_2_06" src="./assets/img/section_2_06.webp" />
        </div>
        <div class="image-container">
          <img class="section_2_07" src="./assets/img/section_2_07.webp" />
        </div>
        <div class="image-container">
          <img class="section_2_08" src="./assets/img/section_2_08.webp" />
        </div>
        <div class="image-container">
          <img class="section_2_09" src="./assets/img/section_2_09.webp" />
        </div>
        <div class="image-container">
          <img class="section_2_10" src="./assets/img/section_2_10.webp" />
        </div>
      </div>
      <div class="images-wrapper top">
        <div class="image-container">
          <img class="section_2_01" src="./assets/img/section_2_01.webp" />
        </div>
        <div class="image-container">
          <img class="section_2_02" src="./assets/img/section_2_02.webp" />
        </div>
        <div class="image-container">
          <img class="section_2_03" src="./assets/img/section_2_03.webp" />
        </div>
        <div class="image-container">
          <img class="section_2_04" src="./assets/img/section_2_04.webp" />
        </div>
        <div class="image-container">
          <img class="section_2_05" src="./assets/img/section_2_05.webp" />
        </div>
      </div>
    </section>
    <section class="third-section">
      <h1>Animate Anything You Want</h1>
      <p>Easily add animation to text, photos, buttons & more.</p>
      <div class="images-wrapper">
        <img class="section_3_06" src="./assets/img/section_3_06.webp" />
        <img class="section_3_05" src="./assets/img/section_3_05.webp" />
        <img class="section_3_04" src="./assets/img/section_3_04.webp" />
        <img class="section_3_03" src="./assets/img/section_3_03.webp" />
        <img class="section_3_02" src="./assets/img/section_3_02.webp" />
        <img class="section_3_01" src="./assets/img/section_3_01.webp" />
      </div>
    </section>
    <section class="forth-section">
      <h1>14 Types of Animation</h1>
      <p>With so many different effects, the possibilities are endless.</p>
      <div class="images-wrapper">
        <img class="section_4_01" src="./assets/img/section_4_01.webp" />
        <img class="section_4_02" src="./assets/img/section_4_02.webp" />
        <img class="section_4_03" src="./assets/img/section_4_03.webp" />
        <img class="section_4_04" src="./assets/img/section_4_04.webp" />
      </div>
    </section>
  </div>
</template>

<script>
import VueScrollmagic from "vue-scrollmagic";
import Vue from "vue";
import { gsap } from "gsap";
import { ScrollTrigger } from "gsap/ScrollTrigger";
// import { TimelineMax } from "gsap/"

Vue.use(VueScrollmagic);

export default {
  name: "App",
  components: {},
  mounted() {
    // const ScrollTrigger: gsap.plugins.ScrollTrigger;

    gsap.registerPlugin(ScrollTrigger);

    gsap.from(".section_1_01", {
      scrollTrigger: {
        trigger: ".images-wrapper",
        start: "center-=300px top",
        end: "100%",
        scrub: true,
        // markers: true,
        duration: 300,
        pin: true,
      },
      duration: 300,
      y: -100,
      x: -150,
      ease: "Power3.easeInOut",
    });
    gsap.from(".section_1_02", {
      scrollTrigger: {
        trigger: ".images-wrapper",
        start: "center-=300px top",
        end: "100%",
        scrub: true,
        // markers: true,
        duration: 300,
        pin: true,
      },
      duration: 300,
      y: -150,
      x: -250,
      ease: "Power3.easeInOut",
    });
    gsap.from(".section_1_03", {
      scrollTrigger: {
        trigger: ".images-wrapper",
        start: "center-=300px top",
        end: "100%",
        scrub: true,
        // markers: true,
        duration: 300,
        pin: true,
      },
      duration: 300,
      y: -80,
      x: -100,
      ease: "Power3.easeInOut",
    });
    gsap.from(".section_1_04", {
      scrollTrigger: {
        trigger: ".images-wrapper",
        start: "center-=300px top",
        end: "100%",
        scrub: true,
        // markers: true,
        duration: 300,
        pin: true,
      },
      duration: 300,
      y: -100,
      x: -150,
      ease: "Power3.easeInOut",
    });
    gsap.from(".section_1_05", {
      scrollTrigger: {
        trigger: ".images-wrapper",
        start: "center-=300px top",
        end: "100%",
        scrub: true,
        // markers: true,
        duration: 300,
        pin: true,
      },
      duration: 300,
      y: -80,
      x: -200,
      ease: "Power3.easeInOut",
    });
    gsap.from(".section_1_06", {
      scrollTrigger: {
        trigger: ".images-wrapper",
        start: "center-=300px top",
        end: "100%",
        scrub: true,
        // markers: true,
        duration: 300,
        pin: true,
      },
      duration: 300,
      y: -100,
      x: -350,
      ease: "Power3.easeInOut",
    });
    gsap.from(".section_1_07", {
      scrollTrigger: {
        trigger: ".images-wrapper",
        start: "center-=300px top",
        end: "100%",
        scrub: true,
        // markers: true,
        duration: 300,
        pin: true,
      },
      duration: 300,
      y: -50,
      x: -150,
      ease: "Power3.easeInOut",
    });
    gsap.from(".section_1_08", {
      scrollTrigger: {
        trigger: ".images-wrapper",
        start: "center-=300px top",
        end: "100%",
        scrub: true,
        // markers: true,
        duration: 300,
        pin: true,
      },
      duration: 300,
      y: 50,
      x: -350,
      ease: "Power3.easeInOut",
    });
    gsap.from(".section_1_09", {
      scrollTrigger: {
        trigger: ".images-wrapper",
        start: "center-=300px top",
        end: "100%",
        scrub: true,
        // markers: true,
        duration: 300,
        pin: true,
      },
      duration: 300,
      y: 100,
      x: -200,
      ease: "Power3.easeInOut",
    });
    gsap.from(".section_1_bg", {
      scrollTrigger: {
        trigger: ".images-wrapper",
        start: "center-=300px top",
        end: "100%",
        scrub: true,
        // markers: true,
        duration: 300,
        pin: true,
      },
      duration: 300,
      ease: "Power3.easeInOut",
    });

    gsap.to('.top .image-container',{
      scrollTrigger:{
        trigger:".top",
        start:"top+=200px center+=100px",
        end: "90% center+=100px",
        scrub:true,
        // markers:true,
        duration: 4,
        // pin: true
      },
      opacity:0,
    });

    gsap.to(".section_3_01",{
      scrollTrigger:{
        trigger:".third-section .images-wrapper",
        start:"top+300px center",
        end: "100%",
        scrub:true,
        // markers:true,
        pin:true
      },
      y: -250,
      ease: "Power3.easeInOut"
    })
    gsap.to(".section_3_02",{
      scrollTrigger:{
        trigger:".third-section .images-wrapper",
        start:"top center",
        end: "100%",
        scrub:true,
        // markers:true,
        pin:true
      },
      y: -200,
      ease: "Power3.easeInOut"
    })
    gsap.to(".section_3_03",{
      scrollTrigger:{
        trigger:".third-section .images-wrapper",
        start:"top center",
        end: "100%",
        scrub:true,
        // markers:true,
        pin:true
      },
      y: -100,
      ease: "Power3.easeInOut"
    })
    gsap.to(".section_3_04",{
      scrollTrigger:{
        trigger:".third-section .images-wrapper",
        start:"top center",
        end: "100%",
        scrub:true,
        // markers:true,
        pin:true
      },
      y: 0,
      ease: "Power3.easeInOut"
    })
    gsap.to(".section_3_05",{
      scrollTrigger:{
        trigger:".third-section .images-wrapper",
        start:"top center",
        end: "100% ",
        scrub:true,
        // markers:true,
        pin:true
      },
      y: 150,
      ease: "Power3.easeInOut"
    })
    gsap.to(".section_3_06",{
      scrollTrigger:{
        trigger:".third-section .images-wrapper",
        start:"top center",
        end: "100% ",
        scrub:true,
        // markers:true,
        pin:true
      },
      y: 200,
      ease: "Power3.easeInOut"
    });
    
  },
};
</script>

<style>
* {
  margin: 0%;
  padding: 0%;
  box-sizing: border-box;
}

#app {
  background-color: #d3eefe;
}

h1 {
  font-family: "Poppins";
  color: #43515c;
  font-size: 70px;
  font-weight: lighter;
  letter-spacing: -5px;
  z-index: 2;
}

.first-section {
  width: 100%;
  height: 250vh;
  display: flex;
  align-items: center;
  flex-direction: column;
  text-align: center;
  position: relative;
}

.first-section .images-wrapper {
  position: absolute;
}

.ingredient-images {
  position: absolute;
  width: 28vw;
  left: calc(50% - 28vw);
  height: 530px;
  top: 420px;
}

.section_1_01 {
  position: absolute;
  top: 25px;
  right: 1vw;
}

.section_1_02 {
  position: absolute;
  top: 100px;
  right: 8vw;
}

.section_1_03 {
  position: absolute;
  top: 110px;
  right: 1vw;
}

.section_1_04 {
  position: absolute;
  top: 230px;
  right: 6vw;
}

.section_1_05 {
  position: absolute;
  top: 240px;
  right: 9vw;
}

.section_1_06 {
  position: absolute;
  top: 170px;
  right: 13vw;
}

.section_1_07 {
  position: absolute;
  top: 270px;
  right: 1vw;
}

.section_1_08 {
  position: absolute;
  top: 320px;
  right: 10vw;
}

.section_1_09 {
  position: absolute;
  top: 370px;
  right: 1vw;
}

.second-section {
  width: 100%;
  height: 100vh;
  display: flex;
  align-items: center;
  flex-direction: column;
  text-align: center;
  position: relative;
}

.second-section .images-wrapper {
  position: absolute;
  display: flex;
  padding: 200px 0;
  top: 20%;
  overflow: hidden;
}

.image-container {
  overflow: hidden;
  height: 100%;
}

.third-section {
  width: 100%;
  height: 200vh;
  display: flex;
  align-items: center;
  flex-direction: column;
  text-align: center;
  position: relative;
}

.third-section .images-wrapper {
  margin-top: 300px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.third-section .images-wrapper img {
  position: absolute;
}

.forth-section {
  width: 100%;
  height: 120vh;
  display: flex;
  align-items: center;
  flex-direction: column;
  text-align: center;
  position: relative;
}

.forth-section .images-wrapper {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.forth-section .images-wrapper img {
  position: absolute;
}
</style>