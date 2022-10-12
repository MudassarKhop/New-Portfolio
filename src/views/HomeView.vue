<template>
<div id="homepage">
  <div id="socials">
    <a href="">    <i class="fa-brands fa-github"></i>
</a><a href="">    <i class="fa-brands fa-linkedin"></i>
</a><a href="">    <i class="fa-brands fa-twitter"></i>
</a>
<a href=""><i class="fa-brands fa-instagram"></i></a>
    <div id="line"></div>
  </div>
<div id="title">
<h3>Hi There,</h3>
<h1>I'm <span>Mudassar Khopatkar</span></h1>
<h2>An Aspiring Web-Developer !</h2>
<div id="buttons">
  <button id="b1">RESUME</button>
  <button id="b2">CONTACT ME</button>
</div>
</div>
<div id="picture">
<img id="png" src="https://i.postimg.cc/x1sTCpVB/pngaaa-com-3147707.png" alt="">
</div>
</div>
</template>

<script>
</script>
<style>
@font-face {
  font-family: zaptron ;
  src: url(../assets/Zaptron\ Regular.otf);
}
 #homepage{
  height: 100vh;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-content: center;
 }
 #title{
  /* border: 3px solid red; */
  height: 100%;
  width:44%;
  text-align: start;
  color: white;
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  justify-content: center;
  align-content: flex-start;
  line-height: 80px;
 }
 #title h3{
  font-size: 30px;
  letter-spacing: 2px;
  color: rgb(223, 223, 223);
  text-shadow: 0 5px 5px black;
 }
 #title h1{
  font-size: 65px;
  letter-spacing: 2px;
  color: white;
  text-shadow: 0 5px 5px black;
 }
 #title h2{
  font-size: 45px;
  letter-spacing: 2px;
  color: white;
  text-shadow: 0 5px 5px black;
 }
 #picture{
  /* border: 3px solid red; */
  height: 100%;
  width:44%;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: start;
  align-content: center;
 }
 #socials{
  /* border: 3px solid red; */
  height: 100%;
  width:10%;
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  justify-content: end;
  align-content: flex-start;
margin-left: 30px;
 }
 #buttons{
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: start;
  align-content: flex-start;
  width: 100%;
  gap: 30px;
  margin-top: 60px;
  padding-bottom: 35px;
 }
 button{
  width: 30%;
  height: 70px;
  border-radius: 12px;
  font-size: 25px;
  border: none;
  color: white;
  box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
  text-shadow: 0 4px 4px black;
 }
 #b1{
  background-color: #fd3e57;
 }
 #b2{
background-color: #1e3c6e;
 }
 span{
  color: #fd3e57;
  text-shadow: -4px 3px 0 #0a0e27, -14px 7px 0 #0a0e27;
 }
 .fa-brands{
  color: rgb(223, 223, 223);
  margin-bottom: 25px;
  font-size: 35px;
 }
 #line{
  margin-top: 15px;
  margin-left: 15px;
  width: 0.1px;
  background-color: white;
  border: 3px solid white;
  height: 20%;
 }
 #png{
  width: 80%;
  height: 40%;
 }
</style>
