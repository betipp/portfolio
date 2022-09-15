<template>
  <div class="container d-flex justify-content-center">
    <div class="d-flex justify-content-center min-h-screen items-left col-10">
      <a class="main-font pb-5">About Me 🍊</a>
      <a class="secondery-font"
        >I am a bachelor of Computer and Information Science working on my
        master's in multimedia 🏫
      </a>
      <a class="secondery-font">
        I'm interested in creating fun and interactive websites and have a
        passion for graphic design.</a
      ><br />
      <a class="secondery-font">
        I'm interested in creating fun and interactive websites and have a
        passion for graphic design.
      </a>
      <a class="secondery-font"
        >My hobbies consist of drawing and game development. I am always looking
        for a way to bring ideas to life.🎮🎨</a
      >
    </div>
  </div>
</template>

<style scoped>
a > span {
  -webkit-text-fill-color: initial;
}
span a {
  color: #007db5;
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
  min-height: 50vh;
  flex-direction: column;
}
a {
  text-decoration: none;
  color: #292b2c;
}
</style>
