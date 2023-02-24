<script setup>
import Navbar from './components/Navbar.vue'
import HMT from './components/HMT.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.png"/>

    <div class="wrapper">
      <Navbar msg="You did it!" />
      <HMT />
    </div>
  </header>
</template>

<style scoped>
header{
  width: 100%;
}

.logo {
  position: absolute;
  left: 5.83%;
  right: 87.18%;
  top: 54px;
  bottom: 99.04%;
}
</style>
