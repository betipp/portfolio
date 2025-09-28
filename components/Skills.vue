<template>
  <div class="container d-flex justify-content-center">
    <div class="d-flex min-h-screen items-left col-10">
      <p class="main-font pb-5 pt-5 pt-md-0">Technologies 🔧</p>
      <a class="secondery-font pb-5"
        >This is the list of technologies I have gathered in my toolkit! 🧰</a
      >
      <div class="d-flex flex-wrap">
        <!--
        <a class="p-2">HTML5 + CSS3</a>
        <a class="p-2">JS</a>
        <a class="p-2">Vue</a>
        <a class="p-2">PHP</a>
        <a class="p-2">Java</a>
        <a class="p-2">Android</a>
        <a class="p-2">Python</a>
        <a class="p-2">Git</a>
        <a class="p-2">SQL-database</a>-->
        <i class="fab fa-blender fa-5x pr-4 icon"></i>
        <i class="fab fa-unity fa-5x pr-4 icon"></i>
        <i class="fab fa-html5 fa-5x pr-4 icon"></i>
        <i class="fab fa-js-square fa-5x pr-4 icon"></i>
        <i class="fab fa-vuejs fa-5x pr-4 icon"></i>
        <i class="fab fa-android fa-5x pr-4 icon"></i>
        <i class="fab fa-python fa-5x pr-4 icon"></i>
        <i class="fas fa-database fa-5x pr-4 icon"></i>
        <i class="fab fa-git fa-5x pr-4 icon"></i>
        <i class="fab fa-java fa-5x pr-4 icon"></i>
        <i class="fab fa-php fa-5x pr-4 icon"></i>
      </div>

      <!--Say hello-->
    </div>
  </div>
</template>

<style scoped>
i {
  color: #292b2c;
}

.icon:hover {
  color: #ffa908;
  animation: wiggle 400ms infinite;
  animation-timing-function: linear;
  transition: 0.3s ease-in-out all;
}

@media screen and (max-width: 499px) {
  .icon {
    font-size: 2em;
  }
}

@media screen and (min-width: 500px) and (max-width: 1299px) {
  .icon {
    font-size: 3em;
  }
}

@media screen and (min-width: 1300px) {
  .icon {
    font-size: 5em;
  }
}

@keyframes wiggle {
  0% {
    transform: rotate(0deg);
  }
  25% {
    transform: rotate(-8deg);
  }
  50% {
    transform: rotate(0deg);
  }
  75% {
    transform: rotate(8deg);
  }
  100% {
    transform: rotate(0deg);
  }
}

.main-font {
  font-family: karla, sans-serif;
  font-size: 30px;
  color:  #ffa908;
}
.secondery-font {
  font-family: karla, sans-serif;
  font-size: 20px;
  text-decoration: none;
}
.min-h-screen {
  width: 70%;
  min-height: 60vh;
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
</style>
