<template>
  <div class="justify-center min-h-screen items-center align-self-start pt-0">
    <div class="align-self-start arrow bounce">
      <button @click="scrollToProjects">
        <i class="mt-4 fas fa-arrow-down fa-3x pr-4 linkIcon"></i>
      </button>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    scrollToProjects() {
      const projectsSection = document.getElementById('projects');
      if (projectsSection) {
        projectsSection.scrollIntoView({ behavior: 'smooth' });
      }
    },
  },
};
</script>

<style scoped>
.min-h-screen {
  min-height: 15vh;
}

i {
  color: #ffc14f;
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
</style>
