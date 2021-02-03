<template>
  <div class="p-aboutSarah">
    <div class="p-aboutSarah__background">
      <span class="p-aboutSarah__bubble--yellow"></span>
      <span class="p-aboutSarah__bubble--green"></span>
      <span class="p-aboutSarah__bubble--blue"></span>
      <span class="p-aboutSarah__bubble--red"></span>
    </div>

    <div class="p-aboutSarah__content">
      <section class="p-aboutSarah__about">
        <img
          class="p-aboutSarah__image"
          src="../assets/thatsMe.jpg"
          alt="picture of me, Sarah"/>
        <p class="p-aboutSarah__name">Sarah Eibensteiner</p>
        <p class="p-aboutSarah__profession">Frontend Developer</p>
      </section>

      <section class="p-aboutSarah__textBlock">
        <h1 class="p-aboutSarah__header">Because Frontend is awesome</h1>
        <div class="p-aboutSarah__linkSection">
          <SingleLink 
            class="p-aboutSarah__singleLink"
            filename="file.svg"
            text="Get my CV"
            link="lala" />
          <SingleLink 
            class="p-aboutSarah__singleLink"
            filename="mail.svg"
            text="sarah@eibensteiner.me"
            link="mailto: sarah@eibensteiner.me" />
          <SingleLink
            class="p-aboutSarah__singleLink"
            filename="linkedin.svg"
            text="LinkedIn"
            link="ttps://www.linkedin.com/in/sarah-eibensteiner/" />
        </div>
        <span class="p-aboutSarah__seperator"></span>
        <div class="p-aboutSarah__introText">
          Hi, my name is Sarah and I am thrilled about creating the best user
          experience with ❤️, ☕ and some curly brackets. <br /><br />
          Studying at the UAS in Hagenberg,
          I found the passion for frontend development and 
          <span class="p-aboutSarah__animateButton" @click="startConfetti()">
            got a position @eRecruiter 🎉</span><br />
          Helping others and continue improving me and my work, is what I am seeking for. <br/> <br/>
          I love to travel, especially to colder northern countries (iceland was the best so far).<br/>
          During playing the violin, I often find new ways to solve the weirdest coding issues you can imagine. We all know them, don't we?<br/>
          And most important, I make the best cheesecake (at least my colleagues think so).
          <br /><br />
        </div>
      </section>
    </div>
    <canvas width="700" height="500" id="confetti"></canvas>
  </div>
</template>

<script>
import SingleLink from "../components/SingleLink.vue";

export default {
  name: "About",
  components:{
    SingleLink
  },
  methods: {
    startConfetti() {
      const confetti = require("canvas-confetti");
      const toastContainer = document.querySelector("#confetti");

      var myConfetti = confetti.create(toastContainer, {
        resize: false,
        useWorker: true,
      });
      myConfetti({
        spread: 70,
        origin: { y: 1.2 },
      });
    },  
  }
}
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@500;600&display=swap");

body {
  -webkit-font-smoothing: antialiased;
  font-family: Inter;
  overflow: hidden;
  width: 100%;
  height: 100vh;
}

.p-aboutSarah {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 100vh;
}

.p-aboutSarah__background {
  position: fixed;
  width: 100%;
  height: 100vh;
  overflow: hidden;
}

.p-aboutSarah__animateButton {
  appearance: none;
  color:#1b1f23;
  background: transparent;
  transition: all 0.2s;
}

.p-aboutSarah__animateButton:hover {
   color: #6a737d;
   cursor: pointer;
}

.p-aboutSarah__bubble--yellow {
  position: absolute;
  width: 15%;
  height: 15%;
  min-width: 150px;
  min-height: 150px;
  left: 0px;
  top: 0px;
  background: #f4c54a;
  filter: blur(140px);
}

.p-aboutSarah__bubble--green {
  position: absolute;
  width: 15%;
  height: 15%;
  min-width: 150px;
  min-height: 150px;
  left: 97%;
  top: 15%;
  background: #0b9f5e;
  filter: blur(140px);
}

.p-aboutSarah__bubble--blue {
  position: absolute;
  width: 15%;
  height: 15%;
  min-width: 150px;
  min-height: 150px;
  top: 65%;
  background: #307fe2;
  filter: blur(110px);
}

.p-aboutSarah__bubble--red {
  position: absolute;
  width: 15%;
  height: 15%;
  min-width: 150px;
  min-height: 150px;
  left: 95%;
  top: 95%;
  background: #dd343d;
  filter: blur(140px);
}

.p-aboutSarah__content {
  display: flex;
  width: 100%;
  height: 100%;
  z-index: 5;
  justify-content: center;
  padding-top: 15%;
  background: transparent;
}

canvas {
  position: fixed;
  bottom: 0;
  left: 45vh;
  width: 50vw;
  height: 50vh;
}

.p-aboutSarah__image {
  height: auto;
  width: 168px;
  border-radius: 4px;
}

.p-aboutSarah__name {
  font-family: Inter;
  font-style: normal;
  font-weight: 600;
  font-size: 14px;
  line-height: 20px;
  text-align: right;
  color: #1b1f23;
  margin: 0;
  padding-top: 24px;
  padding-bottom: 8px;
  -webkit-font-smoothing: antialiased;
}

.p-aboutSarah__profession {
  font-family: Inter;
  font-style: italic;
  font-weight: 500;
  font-size: 14px;
  line-height: 20px;
  text-align: right;
  color: #6a737d;
  margin: 0;
  -webkit-font-smoothing: antialiased;
}

.p-aboutSarah__about {
  margin-right: 80px;
}

.p-aboutSarah__textBlock {
  max-width: 45%;
}

.p-aboutSarah__header {
  font-family: Inter;
  font-style: normal;
  font-weight: bold;
  font-size: 26px;
  line-height: 36px;
  color: #1b1f23;
  margin: 0 0 24px 0;
  -webkit-font-smoothing: antialiased;
}

.p-aboutSarah__linkSection {
  display: flex;
  flex-direction: row;
  -webkit-font-smoothing: antialiased;
}

.p-aboutSarah__singleLink {
  display: flex;
  align-items: center;
}

.p-aboutSarah__singleLink:not(:first-child) {
  border-left: 1px solid #e1e4e8;
  padding: 0 16px;
}

.p-aboutSarah__singleLink:first-child {
  padding-right: 16px;
}

.p-aboutSarah__seperator {
  display: block;
  border-bottom: 1px dashed #e1e4e8;
  width: 100%;
  padding-top: 30px;
}

.p-aboutSarah__introText {
  font-family: Inter;
  display: block;
  width: 100%;
  padding-top: 30px;
  font-weight: 500;
  font-size: 16px;
  line-height: 32px;
  color: #6a737d;
  -webkit-font-smoothing: antialiased;
}

@media all and (max-width: 680px) {
  .p-aboutSarah__content {
    display: inline-block;
    max-width: 90vw;
    padding-top: 0;
    margin: 24px;
  }

  .p-aboutSarah__textBlock {
    max-width: 90%;
  }

  .p-aboutSarah__about {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding-bottom: 32px;
    margin-right: 0;
    margin-top: 24px;
  }

  .p-aboutSarah__linkSection {
    flex-direction: column;
  }

  .p-aboutSarah__singleLink:not(:first-child) {
    border: none;
    padding: 0 0 12px 0;
  }

  .p-aboutSarah__singleLink:first-child {
    padding: 0 0 12px 0;
  }

  canvas {
    left: 5vw;
    width: 90vw;
    height: 50vh;
  }
}
</style>
