<template>
  <div class="d-flex justify-content-end secondery-font pt-2">
    <div
      id="myNav"
      :class="{ openedNav: showNavbar, closedNav: !showNavbar }"
      @wheel.prevent
      @touchmove.prevent
      @scroll.prevent
    >
      <div
        class="
          d-flex
          justify-content-center
          col-12
          h-100
          secondery-font
          pt-2
          text-white
          align-items-start
          flex-wrap
        "
      >
        <div
          class="closebtn d-flex justify-content-end col-12"
          @click="closeNavigation"
        >
          <i class="fa fa-times"></i>
        </div>
        <br />

        <div
          class="
            d-flex
            align-items-center
            text-align-center
            navbar-content
            p-2
            flex-wrap
          "
        >
          <p class="pl-4 pr-4 d-none d-block text-center p-2 col-12">
            My Projects
          </p>

          <p class="pl-4 pr-4 d-none d-block text-center p-2 col-12">
            About Me
          </p>

          <p class="pl-4 pr-4 d-none d-block text-center p-2 col-12">
            Technologies
          </p>

          <p class="pl-4 pr-4 d-none d-block text-center p-2 col-12">Contact</p>
        </div>
      </div>
    </div>
    <div class="openbtn p-1 pr-4">
      <i class="fa fa-bars" @click="openNavigation"></i>
    </div>
    <router-view />
  </div>
</template>

<script>
export default {
  data() {
    return {
      showNavbar: false,
    }
  },
  methods: {
    openNavigation: function () {
      this.showNavbar = true
    },
    closeNavigation: function () {
      this.showNavbar = false
    },
  },
}
</script>

<style>
.navbar-content {
  z-index: 2;
  color: white;
}
.openedNav {
  width: 100vw;
  height: 100vh;
  position: fixed;
  z-index: 1;
  background-color: #fcb177;
}

.closedNav {
  height: 0vh;
  z-index: 1;
  display: none;
}

.secondery-font {
  font-family: karla, sans-serif;
  font-size: 25px;
  text-decoration: none;
}
</style>
