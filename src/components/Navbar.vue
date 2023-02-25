<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="header">
    <div class="navitems">
      <a class="navitem" href="#">Products</a>
      <a class="navitem" href="#">Code</a>
      <a class="navitem" href="#">Ecosystem</a>
      <a class="navitem" href="#">Team</a>
      <a class="navitem" href="#">Resources</a>
    </div>
    <div class="joinBtn"><img src="../assets/joinBtn.png"></div>
  </div>
</template>

<style scoped>
@media only screen and (max-width: 600px) {
  .header{
    display: none;
  }
}
.navitems {
  position: absolute;
  display: flex;
  justify-content: space-evenly;
  width: 30.5%;
  left: 54.59%;
  top: 54px;
}

.joinBtn{
  right:0px;
  position: absolute;
}


.navitem {
  font-family: 'Alliance No.1';
  font-style: normal;
  font-weight: 600;
  font-size: 16px;
  line-height: 24px;
  color: #320A8D;
}

</style>
