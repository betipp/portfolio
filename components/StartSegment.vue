<template>
  <div
    class="
      d-flex
      justify-content-center
      min-h-screen
      items-center
      pt-0
      flex-wrap
      vh-90
    "
  >
    <link
      href="https://cdn.jsdelivr.net/npm/tailwindcss@2.1.2/dist/tailwind.min.css"
      rel="stylesheet"
    />
    <div class="p-5 rounded title mr-5">
      <p class="h3 pb-2" style="font-family: 'Dongle'; font-size: 60px;">
        Hello, I'm Beti. 👋
      </p>
      <p class="">
        A developer with a passion for graphic design and game development.
      </p>
    </div>
    <img
      id="profileImage"
      class="bounce d-none d-lg-block"
      style="transform-origin: bottom"
      src="../static/pic.png"
      alt="profile"
    />
  </div>
</template>

<style scoped>

@font-face {
  font-family: "Dongle";
  src: url('../assets/Dongle-Bold.ttf');
}

.title {
  background-color: #ffa600;
  color: white;
  font-family: 'Courier New', monospace;
  transition: 0.5s;
}
img {
  width: 170px;
  height: 170px;
  animation-duration: 2s;
  animation-iteration-count: infinite;
}

.min-h-screen {
  min-height: 92vh;
}

.title:hover {
  box-shadow: 20px 20px 20px rgba(33, 33, 33, 0.2);
  margin-top: -1rem;
}

.title:hover ~ #profileImage {
  animation-name: bounce;
  animation-timing-function: ease;
}

.bounce {
}
@keyframes bounce {
  0% {
    transform: scale(1, 1) translateY(0);
  }
  10% {
    transform: scale(1.1, 0.9) translateY(0);
  }
  30% {
    transform: scale(0.9, 1.1) translateY(-50px);
  }
  50% {
    transform: scale(1, 1) translateY(0);
  }
  100% {
    transform: scale(1, 1) translateY(0);
  }
}
</style>
