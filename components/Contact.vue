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
                >If you wanna say hello or ask about a project, you can find me
                here!</a
              ><br />

              <div class="linkIcon">
                <a
                  href="https://github.com/betipp"
                  target="_blank"
                  style="text-decoration: none  color: white;"
                  class="mt-4 fab fa-github fa-5x pr-4 linkIcon"
                ></a>
                <a
                  href="mailto:betipisc@gmail.com"
                  style="text-decoration: none  color: white;"
                  class="mt-4 fas fa-envelope-open-text fa-5x pr-4 linkIcon"
                ></a>
                <a
                  href="https://pompam.itch.io/"
                  target="_blank"
                  style="text-decoration: none  color: white;"
                  class="fab fa-itch-io fa-5x pr-4 icon linkIcon"
                ></a>
              </div>
            </div>

            <!--Say hello-->
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
/*a {
  font-weight: bold;
}*/

.linkIcon:hover {
  color: #292b2c;
  -webkit-transition: color 1s;
  -moz-transition: color 1s;
  -ms-transition: color 1s;
  -o-transition: color 1s;
  transition: color 1s;
}
.linkIcon {
  color: #fff;
}

.main-font {
  font-family: karla, sans-serif;
  font-size: 30px;
  color: orangered;
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
  color: #292b2c;
}
img {
  width: 80px;
  height: 80px;
}

.bgColor {
  background-color: #fcb177;
}

/* Zig zag stuff */

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
  background: linear-gradient(-45deg, #fcb177 16px, transparent 0),
    linear-gradient(45deg, #fcb177 16px, transparent 0);
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
  background: #fcb177;
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
