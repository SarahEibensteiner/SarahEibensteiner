<template>
  <div class="p-thatsMe">
    <div class="p-thatsMe__background">
      <span class="p-thatsMe__bubble--yellow"></span>
      <span class="p-thatsMe__bubble--green"></span>
      <span class="p-thatsMe__bubble--blue"></span>
      <span class="p-thatsMe__bubble--red"></span>
    </div>

    <div class="p-thatsMe__content">
      <section class="p-thatsMe__about">
        <img class="p-thatsMe__image" src="../assets/me3.jpg" />
        <p class="p-thatsMe__name">Sarah Eibensteiner</p>
        <p class="p-thatsMe__profession">Frontend Developer</p>
      </section>

      <section class="p-thatsMe__textBlock">
        <h1 class="p-thatsMe__header">Because Frontend is awesome</h1>
        <div class="p-thatsMe__linkSection">
          <div class="p-thatsMe__singleLink">
            <svg
              width="14"
              height="14"
              viewBox="0 0 14 14"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M11.6667 12.8333H2.33333C2.17862 12.8333 2.03025 12.7718 1.92085 12.6624C1.81146 12.553 1.75 12.4047 1.75 12.25V1.74996C1.75 1.59525 1.81146 1.44688 1.92085 1.33748C2.03025 1.22808 2.17862 1.16663 2.33333 1.16663H11.6667C11.8214 1.16663 11.9697 1.22808 12.0791 1.33748C12.1885 1.44688 12.25 1.59525 12.25 1.74996V12.25C12.25 12.4047 12.1885 12.553 12.0791 12.6624C11.9697 12.7718 11.8214 12.8333 11.6667 12.8333ZM4.66667 4.08329V5.24996H9.33333V4.08329H4.66667ZM4.66667 6.41663V7.58329H9.33333V6.41663H4.66667ZM4.66667 8.74996V9.91663H7.58333V8.74996H4.66667Z"
                fill="#6A737D"
              />
            </svg>
            <a href="lala"> Get my CV </a>
          </div>
          <div class="p-thatsMe__singleLink">
            <svg
              width="14"
              height="14"
              viewBox="0 0 14 14"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M1.3085 3.99816L6.70258 0.764161C6.79324 0.709765 6.89698 0.68103 7.00271 0.68103C7.10843 0.68103 7.21217 0.709765 7.30283 0.764161L12.6917 3.99874C12.7349 4.02465 12.7707 4.06132 12.7955 4.10518C12.8204 4.14904 12.8334 4.19859 12.8334 4.24899V11.6667C12.8334 11.8214 12.772 11.9697 12.6626 12.0791C12.5532 12.1885 12.4048 12.25 12.2501 12.25H1.75008C1.59537 12.25 1.447 12.1885 1.3376 12.0791C1.22821 11.9697 1.16675 11.8214 1.16675 11.6667V4.24841C1.16674 4.198 1.17979 4.14846 1.20463 4.1046C1.22948 4.06074 1.26526 4.02407 1.3085 3.99816ZM10.7019 4.80899L7.03566 7.98174L3.29416 4.80549L2.53933 5.69449L7.04266 9.51824L11.4649 5.69158L10.7019 4.80899V4.80899Z"
                fill="#6A737D"
              />
            </svg>
            <a href="lala"> sarah@eibensteiner.me </a>
          </div>
          <div class="p-thatsMe__singleLink">
            <svg
              width="14"
              height="14"
              viewBox="0 0 14 14"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M10.6954 10.6977H9.14083V8.26117C9.14083 7.68017 9.12917 6.93233 8.33 6.93233C7.51975 6.93233 7.39608 7.56467 7.39608 8.21858V10.6977H5.84092V5.6875H7.33425V6.37H7.35467C7.5635 5.97683 8.071 5.56092 8.82933 5.56092C10.4043 5.56092 10.696 6.59808 10.696 7.94733V10.6977H10.6954ZM4.08508 5.00208C3.96641 5.00224 3.84887 4.97897 3.7392 4.9336C3.62954 4.88824 3.52991 4.82168 3.44602 4.73774C3.36213 4.65379 3.29563 4.55412 3.25034 4.44442C3.20505 4.33473 3.18185 4.21718 3.18208 4.0985C3.1822 3.9199 3.23527 3.74535 3.33459 3.59692C3.43391 3.44849 3.57501 3.33284 3.74006 3.2646C3.9051 3.19636 4.08668 3.17859 4.26182 3.21355C4.43696 3.2485 4.59781 3.33461 4.72401 3.46098C4.85022 3.58735 4.93612 3.7483 4.97085 3.92349C5.00557 4.09868 4.98758 4.28023 4.91912 4.44519C4.85067 4.61014 4.73484 4.7511 4.58628 4.85022C4.43772 4.94935 4.2631 5.0022 4.0845 5.00208H4.08508ZM4.86442 10.6977H3.30517V5.6875H4.865V10.6977H4.86442ZM11.4742 1.75H2.52525C2.09592 1.75 1.75 2.08833 1.75 2.50658V11.4934C1.75 11.9117 2.0965 12.25 2.52467 12.25H11.4718C11.9 12.25 12.25 11.9117 12.25 11.4934V2.50658C12.25 2.08833 11.9 1.75 11.4718 1.75H11.4736H11.4742Z"
                fill="#6A737D"
              />
            </svg>
            <a href="lala"> linkedin </a>
          </div>
        </div>
        <span class="p-thatsMe__seperator"></span>
        <div class="p-thatsMe__introText">
          Hi, my name is Sarah and I am thrilled about creating the best user
          experience with ❤️, ☕ and some curly brackets. <br /><br />
          Studying at the UAS in Hagenberg,
          I found the passion for frontend development and 
          <span class="p-thatsMe__animateButton" @click="startConfetti()">
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
    <canvas width="1000" height="800" id="snow"></canvas> 
  </div>
</template>

<script>
export default {
  name: "ThatsMe",
  props: {
    msg: String,
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

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@500;600&display=swap");

body {
  -webkit-font-smoothing: antialiased;
  font-family: Inter;
  overflow: hidden;
  width: 100%;
  height: 100vh;
}

.p-thatsMe__background {
  width: 100%;
  height: 100vh;
  overflow: hidden;
}

.p-thatsMe__animateButton {
  border: 0;
  border-radius: 4px;
  appearance: none;
  color:#1b1f23;
  background: transparent;
  transition: all 0.2s;
}

.p-thatsMe__animateButton:hover {
   color: #6a737d;
   cursor: pointer;
}

.p-thatsMe__bubble--yellow {
  position: absolute;
  width: 15%;
  height: 15%;
  left: 0px;
  top: 0px;
  background: #f4c54a;
  filter: blur(140px);
}

.p-thatsMe__bubble--green {
  position: absolute;
  width: 15%;
  height: 15%;
  left: 97%;
  top: 15%;
  background: #0b9f5e;
  filter: blur(140px);
}

.p-thatsMe__bubble--blue {
  position: absolute;
  width: 15%;
  height: 15%;
  top: 65%;
  background: #307fe2;
  filter: blur(110px);
}

.p-thatsMe__bubble--red {
  position: absolute;
  width: 15%;
  height: 15%;
  left: 95%;
  top: 95%;
  background: #dd343d;
  filter: blur(140px);
}

.p-thatsMe__content {
  display: flex;
  position: absolute;
  top: 0;
  left: 0;
  z-index: 5;
  justify-content: center;
  padding-top: 10%;
  background: transparent;
}

canvas {
  width: 50vw;
  height: 50vh;
  position: absolute;
  bottom: 0;
  left: 45vh;
}

.p-thatsMe__image {
  height: auto;
  width: 168px;
  border-radius: 4px;
}

.p-thatsMe__name {
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

.p-thatsMe__profession {
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

.p-thatsMe__about {
  margin-right: 80px;
}

.p-thatsMe__textBlock {
  max-width: 45%;
}

.p-thatsMe__header {
  font-family: Inter;
  font-style: normal;
  font-weight: bold;
  font-size: 26px;
  line-height: 36px;
  color: #1b1f23;
  margin: 0 0 24px 0;
  -webkit-font-smoothing: antialiased;
}

.p-thatsMe__linkSection {
  display: flex;
  flex-direction: row;
  -webkit-font-smoothing: antialiased;
}

.p-thatsMe__singleLink {
  display: flex;
  align-items: center;
}

.p-thatsMe__singleLink:not(:first-child) {
  border-left: 1px solid #e1e4e8;
  padding: 0 16px;
}

.p-thatsMe__singleLink:first-child {
  padding-right: 16px;
}

.p-thatsMe__singleLink svg {
  padding-right: 8px;
}

.p-thatsMe__singleLink a {
  font-family: Inter;
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  color: #2f363d;
  text-decoration: none;
  -webkit-font-smoothing: antialiased;
}

.p-thatsMe__seperator {
  display: block;
  border-bottom: 1px dashed #e1e4e8;
  width: 100%;
  padding-top: 30px;
}

.p-thatsMe__introText {
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
</style>
