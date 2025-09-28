<template>
  <div class="container pt-4 projects-section" id="projects" >
    <div class="d-flex justify-content-center text-left">
      <p
        class="text-left col-10"
        style="
          font-family: karla, sans-serif;
          font-size: 30px;
          color: #ffa908;
        "
      >
        My Projects 🗄️
      </p>
    </div>
    <div>
      <div class="d-flex justify-content-center col-12 row">
        <div
          class="
            d-flex
            justify-center justify-content-center
            rounded
            col-12 col-lg-6
            p-2
            box zoomies-bg
          "
        >
          <p class="main-font col-12">Zoomies</p>
          <br />

          <a class="second-font col-12 p-2"
            >A 3D game where you play as a cat destroying your owner's propery.
          </a>
          <a class="second-font p-2">Unity</a>
          <a class="second-font p-2">Blender</a>
          <a class="second-font p-2">C#</a>
          <br />

          <div class="col-12">
            <a
              href="https://pompam.itch.io/zoomies"
              target="_blank"
              class="fab fa-itch-io fa-5x pr-4 icon"
            ></a>
          </div>
        </div>
        <div
          class="
            d-flex
            justify-center
            align-items-center
            rounded
            col-12 col-lg-4
            p-2
            box
          "
        >
          <p class="main-font col-12">Pilea Web</p>
          <a class="second-font col-12"
            >Pilea is a plant watering tracker, made in .NET for a University
            class.</a
          >
          <a class="second-font p-2">.NET</a>
          <a class="second-font p-2">HTML+CSS</a>
          <a class="second-font p-2">JS</a>
          <div class="col-12">
            <a
              href="https://github.com/betipp/pilea-web"
              target="_blank"
              class="fab fa-github fa-4x pr-4 icon"
            ></a>
          </div>
        </div>
      </div>

      <div class="d-flex justify-content-center col-12 row">
        <div
          class="
            d-flex
            justify-center
            align-items-center
            rounded
            col-12 col-lg-4
            p-2
            box
          "
        >
          <p class="main-font">PolyKingdom</p>
          <a class="second-font"
            >PolyKingdom is an OpenGL game, made for a University class.</a
          >
          <a class="second-font p-2">Java</a>
          <a class="second-font p-2">libGDX</a>
          <a class="second-font p-2">Android studio</a>

          <div class="col-12">
            <a
              href="https://betipp.github.io/PolyKingdom/"
              target="_blank"
              class="fas fa-gamepad fa-4x pr-4 icon"
            ></a>
            <a
              href="https://github.com/betipp/PolyKingdom"
              target="_blank"
              class="fab fa-github fa-4x pr-4 icon"
            ></a>
          </div>
        </div>
        <div
          class="
            d-flex
            justify-center
            align-items-center
            rounded
            col-12 col-lg-6
            p-2
            box kindle-bg
          "
        >
          <p class="main-font col-12">Kindle</p>
          <a class="second-font"
            >A side-scrolling adventure game, inspired by The Last Campfire</a
          >
          <a class="second-font p-2">Java</a>
          <a class="second-font p-2">libGDX</a>
          <a class="second-font p-2">Aseprite</a>
          <br />

          <div class="col-12">
            <a
              href="https://pompam.itch.io/kindle"
              target="_blank"
              class="fab fa-itch-io fa-5x pr-4 icon"
            ></a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
a {
  text-decoration: none;
}
.icon {
  text-decoration: none;
  transition: transform 0.3s ease-in-out;
}
.icon:hover {
  animation: wobble 0.5s ease-in-out infinite;
}

@keyframes wobble {
  0%,
  100% {
    transform: rotate(0deg);
  }
  25% {
    transform: rotate(-5deg);
  }
  50% {
    transform: rotate(5deg);
  }
  75% {
    transform: rotate(-5deg);
  }
}
.box {
  text-align: center;
  background-color: #ffc14f;
  flex-direction: row;
  flex-wrap: wrap;
  height: 350px;
  color: white;
  margin-left: 2rem;
  margin-top: 3rem;
  transition: 0.3s;
  position: relative;
  overflow: hidden;
}

.box::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(255, 255, 255, 0); /* No tint by default */
  transition: background-color 0.3s ease-in-out;
  z-index: 0;
}

.box:hover::before {
  background-color: rgba(255, 255, 255, 0.8); /* White tint on hover */
}

.box > * {
  position: relative;
  z-index: 1;
}

.box:hover {
  background-color: rgb(212, 120, 23);
  color: #ffa908;
  -webkit-transition: all 0.5s ease-in-out;
  -moz-transition: all 0.5s ease-in-out;
  -o-transition: all 0.5s ease-in-out;
  transition: all 0.5s ease-in-out;
  -webkit-transform: scale(1.05, 1.05);
  transform: scale(1.05, 1.05);
}

@font-face {
  font-family: "Dongle";
  src: url('../assets/Dongle-Bold.ttf');
}

.main-font {
  font-family: "Dongle";
  font-size: 60px;
  padding: 1rem;
}
.second-font {
  font-family: karla, sans-serif;
  font-size: 20px;
  text-decoration: none;
}
a:hover {
  color: inherit;
}

.min-h-screen {
  width: 90%;
}

.zoomies-bg {
  background-image: url('../assets/ZoomiesBG.png');
  background-size: cover;
  background-position: center;
}

.kindle-bg {
  background-image: url('../assets/KindleBg.png');
  background-size: cover;
  background-position: center;
}
</style>
