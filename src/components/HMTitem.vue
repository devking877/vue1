<script setup>
defineProps({
  source: {
    type: String,
    required: true
  }
})
</script>
<template>
  <div class="HMTitem">
      <img :src="'../src/assets/'+source" />
      <div class="strCCC">Complete Jobs</div>
  </div>
</template>

<style>
.strCCC{
  font-family: 'Alliance No1';
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 24px;
  /* or 171% */

  display: flex;
  align-items: flex-end;
  text-align: center;
  letter-spacing: 0.2px;
  color: #320A8D;

  justify-content: center;
}
.HMTitem{
  background: #FFFFFF;
  border-radius: 10px;
  height: 229px;
  width: 15%;
  text-align: -webkit-center;
}

.HMTitemb {
  background: rgba(12, 32, 213, 0.06);
  filter: blur(28px);
  border-radius: 10px;
  top: 5.11%;
  height: 229px;
}
</style>
