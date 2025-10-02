<template>
  <div id="d-wrapper">
    <div class="zig-zag-top">
      <div class="d-flex justify-content-center bgColor">
        <div class="container d-flex justify-content-center">
          <div
            class="
              d-flex
              justify-content-center
              min-h-screen
              items-left
              col-10
              p-4
            "
          >
            <p class="main-font">I'm here! 📧</p>
            <div class="">
              <a class="secondery-font"
                >If you want to say hello or ask about a project, you can find me
                here!</a
              >
              <br />
              <div class="icon-container mt-2">
                <img
                  href="https://github.com/betipp"
                  target="_blank"
                  style="text-decoration: none;"
                  class="linkIcon filter-white mr-1"
                  src="../assets/Icons/icon_github.svg"
                />
              </div>
              <div class="icon-container">
                <img
                  href="mailto:betipisc@gmail.com"
                  style="text-decoration: none; color: white;"
                  class="linkIcon filter-white mr-1"
                  src="../assets/Icons/icon_mail.svg"
                />
              </div>
              <div class="icon-container">
                <img
                  href="https://pompam.itch.io/"
                  target="_blank"
                  style="text-decoration: none; color: white;"
                  class="linkIcon filter-white mr-1"
                  src="../assets/Icons/icon_itchIo.svg"
                />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.icon-container {
  display: inline-block; 
  margin-right: 1rem; 
}

.linkIcon {
  text-decoration: none;
  color: #fff;
  transition: transform 0.3s ease-in-out;
  position: relative;
}

.filter-white{
  filter: invert(98%) sepia(98%) saturate(10%) hue-rotate(214deg) brightness(101%) contrast(102%);
}

.linkIcon:hover {
  animation: wiggle 0.5s ease-in-out infinite;
}

@keyframes wiggle {
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

.main-font {
  font-family: karla, sans-serif;
  font-size: 30px;
  color: #ffa908;
}
.secondery-font {
  font-family: karla, sans-serif;
  font-size: 20px;
  text-decoration: none;
}
.min-h-screen {
  width: 70%;
  min-height: 30vh;
  flex-direction: column;
}
a {
  text-decoration: none;
  color: #fff;
}
img {
  width: 80px;
  height: 80px;
}

.bgColor {
  background-color: #ffc14f;
}

#d-wrapper {
  background-color: #fff;
  color: white;
}
#d-wrapper * {
  margin: 0;
  padding: 0;
}

#d-wrapper div.sep {
  min-height: 200px;
  padding: 32px 0;
}

#d-wrapper .zig-zag-top:before {
  background: linear-gradient(-45deg, #ffc14f 16px, transparent 0),
    linear-gradient(45deg, #ffc14f 16px, transparent 0);
  background-position: left top;
  background-repeat: repeat-x;
  background-size: 22px 32px;
  content: ' ';
  display: block;

  height: 32px;
  width: 100%;

  position: relative;
  bottom: 64px;
  left: 0;
}

#d-wrapper .zig-zag-top {
  margin-bottom: 0;
  background: #ffc14f;
}

#d-wrapper .zig-zag-top {
  padding: 32px 0;
}

#d-wrapper p,
#d-wrapper h1 {
  font-size: 2em;

  color: #fff;
  font-family: 'PT Sans Narrow', 'Fjalla One', sans-serif;

  text-shadow: 1px 1px 0 #cc6516, 2px 2px 0 #cc6516, 3px 3px 0 #cc6516,
    4px 4px 0 #cc6516, 5px 5px 0 #cc6516;
}

#d-wrapper div.sep p,
#d-wrapper div.sep h1 {
  text-shadow: 1px 1px 0 #888, 2px 2px 0 #888, 3px 3px 0 #888, 4px 4px 0 #888,
    5px 5px 0 #888;
  color: #fff;
}

#d-wrapper h1 {
  font-size: 4em;
}

#d-wrapper .zig-zag-bottom:after {
  background: linear-gradient(-45deg, transparent 16px, #1ba1e2 0),
    linear-gradient(45deg, transparent 16px, #1ba1e2 0);
  background-repeat: repeat-x;
  background-position: left bottom;
  background-size: 22px 32px;
  content: '';
  display: block;

  width: 100%;
  height: 32px;

  position: relative;
  top: 64px;
  left: 0px;
}

#d-wrapper p:not(:last-child) {
  margin-bottom: 20px;
}

p {
}
.auth {
  text-decoration: overline;
  color: #999;
  font-size: 2em;
}
</style>
