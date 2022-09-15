<!-- Please remove this file from your project -->
<template>
  <div class="justify-center min-h-screen items-center align-self-start pt-0">
    <div class="align-self-start arrow bounce">
      <button>
        <fa icon="arrow-down" class="fa-2x" />
      </button>
    </div>
  </div>
</template>

<style scoped>
.min-h-screen {
  min-height: 15vh;
}

/*<-- BUTTON CSS  -->*/

a {
  color: white;
  text-decoration: none;
}

.arrow {
  text-align: center;
}
.bounce {
  -moz-animation: bounce 2s infinite;
  -webkit-animation: bounce 2s infinite;
  animation: bounce 2s infinite;
}

@keyframes bounce {
  0%,
  20%,
  50%,
  80%,
  100% {
    transform: translateY(0);
  }
  40% {
    transform: translateY(-30px);
  }
  60% {
    transform: translateY(-15px);
  }
}

/*<-- END OF BUTTON CSS  -->*/
</style>
