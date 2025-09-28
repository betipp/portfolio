<template>
  <div class="container d-flex justify-content-center">
    <div class="d-flex justify-content-center min-h-screen items-left col-10">
      <a class="main-font pb-5">About Me 🍊</a>
      <a class="secondery-font"
        >I am a bachelor of Computer and Information Science.🏫 </a
      ><br />
      <a class="secondery-font">
        In love bringing ideas to life through programming and design.
        VFX and 3D modeling let me express my creativity. ✨</a
      >
      <a class="secondery-font">
        I am also interested in graphic design and creating fun and interactive
        websites.</a
      ><br />
      <a class="secondery-font"
        >My hobbies consist of arts and crafts and game development. I am always looking
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
  color:  #ffa908;
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
