<script setup>
</script>

<template>
  <div class="hmt">
    <div class="hmtBg"></div>
    <div class="hmtl">
      <img src="../assets/hmt_text.png"><br>
      <img src="../assets/hmt_learnbtn.png">
    </div>
    <img style="top:22.8%; position:absolute" src="../assets/hmt_r.png">
    <div class="hmtb">
      <img style="width:608px" src="../assets/hmt_below.png">
      <div class="hmtText"><font color="#6309FF">HMT</font> funds the processing of digitized work, and rewards workers for their contributions.</div>
    </div>
    <div class="tokenDetailbg">
      <div class="tokencenterbg">
        <div class="tokenText">Token Details</div><br>
        <img style="width: 100%; transform: translateX(-5%);" src="../assets/detailCard.png">
        <div style="display: flex;">
          <img src="../assets/tokenTypeBtn.png" style="width:33%">
          <img src="../assets/contactbg.png" style="width:63%">
          <div style="display: flex; height: 80px; left:50%; position:absolute">
            <img src="../assets/etherBtn.png">
            <img src="../assets/polyBtn.png">
          </div>
        </div>
        <div style="display: flex; justify-content: space-between;">
          <div class="loreBtn"><div class="ttt">Smart contract audit:</div><div class="rrr">Loremipsum</div></div>
          <div class="loreBtn"><div class="ttt">Escrow Factory:</div><div class="rrr">Loremipsum</div></div>
        </div>
      </div>
    </div>
    <div class="humanMediabg">
      <div class="mediaTxt">HUMAN in the media</div>
      <img src="../assets/mediaCards.png" style="width:100%; top: 300px; position: relative;">
    </div>
    <img src="../assets/tokenallo.png" style="top:368%; position:absolute; width: 60%; left: 20%;">
    <img src="../assets/supTime.png" style="top:447%; position:absolute; width: 60%; left: 20%;">
    <div class="howHMTbg">
      <div class="howText">How do i get HMT?</div>
    </div>
  </div>
</template>

<style>
.howText{
  font-family: 'Alliance No.1';
  font-style: normal;
  font-weight: 600;
  font-size: 60px;
  line-height: 72px;
  /* identical to box height, or 120% */

  letter-spacing: -0.4px;
  color: #320A8D;
  left: 50%;
  transform: translateX(-50%);
  position:absolute;
  top:103px;
}

.howHMTbg{
  background: linear-gradient(167.14deg, #F0F2FC 9.58%, #FFFFFF 93.46%);
  width: 80%;
  left: 10%;
  position:absolute;
  top: 530%;
  height: 427px;
}

.mediaTxt{
  font-family: 'Alliance No.1';
  font-style: normal;
  font-weight: 600;
  font-size: 50px;
  line-height: 72px;
  top:101px;
  text-align: center;
  letter-spacing: -0.4px;
  color: #320A8D;
  position:absolute;
  left:50%;
  transform: translateX(-50%);
}

.humanMediabg{
  background: #F2F2FA;
  border-radius: 40px;
  top:284%;
  width: 80%;
  position:absolute;
  height: 658px;
  left: 10%;
}

.ttt{
  font-family: 'Alliance No.1';
  font-style: normal;
  font-weight: 600;
  font-size: 18px;
  line-height: 32px;
  letter-spacing: 0.3px;
  color: #FFFFFF;
}

.rrr{
  font-family: 'Alliance No1';
  font-style: normal;
  font-weight: 400;
  font-size: 32px;
  line-height: 48px;
  letter-spacing: 0.15px;
  color: #FFFFFF;
}

.loreBtn{
  background: #320A8D;
  border-radius: 25px;
  display: flex;
  justify-content: space-evenly;
  width: 45%;
  align-items: center;
}

.tokenCard {
  background: #FFFFFF;
  border-radius: 30px;
  height: 320px;
}

.tokenText {
  font-family: 'Alliance No.1';
  font-style: normal;
  font-weight: 600;
  font-size: 60px;
  line-height: 72px;
  /* or 120% */

  letter-spacing: -0.4px;
  color: #320A8D;
}

.hmt{
  display: flex;
  justify-content: flex-end;
}

.hmtBg{
  position: absolute;
  width: 92.5%;
  left: 50%;
  transform: translateX(-50%);
  height: 680px;
  top:11.1%;
  background: #F2F2FA;
  border-radius: 40px;
  z-index: -5;
}

.hmtl{
  position: absolute;
  left: 8.9%;
  top: 32%;
}

.hmtb{
  position: absolute;
  left:14%;
  top: 95.6%;
  display: flex;
  align-items: center;
}

.hmtText{
  font-family: 'Alliance No1';
  font-style: normal;
  font-weight: 400;
  font-size: 48px;
  line-height: 56px;
  letter-spacing: 0.15px;
  color: #320A8D;
}

.tokenDetailbg{
  position:absolute;
  top:171%;
  height: 991px;
  width: 100%;
  background: linear-gradient(167.14deg, #F0F2FC 9.58%, #FFFFFF 93.46%);
}

.tokencenterbg {
  width: 60%;
  left: 50%;
  transform: translateX(-50%);
  position:relative;
  top: 143px;
}
</style>
