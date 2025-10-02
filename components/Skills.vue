<template>
  <div class="container d-flex justify-content-center">
    <div class="d-flex min-h-screen items-left col-10">
      <p class="main-font pb-5 pt-5 pt-md-0">Technologies 🔧</p>
      <a class="secondery-font pb-5"
        >This is the list of technologies I have gathered in my toolkit! 🧰</a
        >
      <div class="d-flex flex-wrap">
        <img class="icon mr-1" src="../assets/Icons/icon_unity.svg"/>
        <img class="icon mr-1" src="../assets/Icons/icon_html.svg"/>
        <img class="icon mr-1" src="../assets/Icons/icon_js.svg"/>
        <img class="icon mr-1" src="../assets/Icons/icon_vue.svg"/>
        <img class="icon mr-1" src="../assets/Icons/icon_android.svg"/>
        <img class="icon mr-1" src="../assets/Icons/icon_php.svg"/>
        <img class="icon mr-1" src="../assets/Icons/icon_database.svg"/>
        <img class="icon mr-1" src="../assets/Icons/icon_git.svg"/>
        <img class="icon mr-1" src="../assets/Icons/icon_java.svg"/>
        <img class="icon mr-1" src="../assets/Icons/icon_php.svg"/>
      </div>
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
  filter: invert(55%) sepia(82%) saturate(524%) hue-rotate(358deg) brightness(104%) contrast(108%);
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
