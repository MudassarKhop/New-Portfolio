<template>
  <div id="socials">
    <a href="https://github.com/MudassarKhop" target="_blank">    <i class="fa-brands fa-github"></i>
</a><a href="https://www.linkedin.com/in/mudassar-khopatkar-a9854023a/" target="_blank">    <i class="fa-brands fa-linkedin"></i>
</a><a href="https://twitter.com/MudathierKop" target="_blank">    <i class="fa-brands fa-twitter"></i>
</a>
<a href="https://www.instagram.com/mudathierkop/" target="_blank"><i class="fa-brands fa-instagram"></i></a>
    <div id="line"></div>
  </div>
<div id="title">
<h3>HI THERE,</h3>
<h1>I'M <span>Mudassar Khopatkar</span></h1>
<h2>AN ASPIRING WEB-DEVELOPER </h2>
<div id="buttons">
  <button id="b1">RESUME</button>
  <button id="b2">CONTACT ME</button>
</div>
<div class="png2">
  <img id="png2" src="https://i.postimg.cc/VNmx3t74/image.png" alt="">
</div>
</div>
<div id="picture">
<img id="png" src="https://i.postimg.cc/x1sTCpVB/pngaaa-com-3147707.png" alt="">
</div>
</template>
<script>
export default {
    
}
</script>
<style>
     #homepage{
  height: 101vh;
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
  
 }
 #title h3{
  font-size: 25px;
  letter-spacing: 2px;
  color: rgb(223, 223, 223);
  text-shadow: 0 5px 5px black;
  margin-bottom: 30px;
  font-weight:500 ;
 }
 #title h1{
  font-size: 45px;
  letter-spacing: 4px;
  color: rgb(223, 223, 223);
  text-shadow: 0 5px 5px black;
  margin-bottom: 30px;
  font-weight: 700;
  }
   #title h2{
  font-size: 30px;
  letter-spacing: 2px;
  color: rgb(223, 223, 223);
  text-shadow: 0 5px 5px black;
  font-weight: 500 ;
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
  margin-top: 30px;
  padding-bottom: 35px;
 }
 button{
  width: 30%;
  height: 70px;
  border-radius: 12px;
  font-size: 25px;
  letter-spacing: 2px;
  border: none;
  color: rgb(223, 223, 223);
  font-family: Pro;
  text-align: center;
  box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
  text-shadow: 0 4px 4px black;
 }
 #b1{
  background-color: #ecb365;
 }
 #b2{
background-color: #0b3447;
 }
 span{
  color: #ecb365;
  text-shadow: -4px 3px 0 #0a0e27, -14px 7px 0 #0a0e27;

 }
 .fa-brands{
  color: rgb(223, 223, 223);
  margin-bottom: 25px;
  font-size: 35px;
  transition: ease 1s;
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
#png2{
  width: 90px;
  height: 90px;
  padding-bottom: 20px ; 
 }
 .png2{
  animation-name: floating;
    animation-duration: 2s;
    animation-iteration-count: infinite;
    animation-timing-function: ease-in-out;
    position: absolute;
    bottom: 0;
    right: 47%;
   translate: middle;
 }
 @keyframes floating {
    0% { transform: translate(0,  0px); }
    50%  { transform: translate(0, 15px); }
    100%   { transform: translate(0, -0px); }   
}
 .fa-linkedin:hover{
  color:#ecb365;
  transition: ease 1s;
 }
 .fa-twitter:hover{
  color:#ecb365;
  transition: ease 1s;
 }
 .fa-github:hover{
  color:#ecb365;
  transition: ease 1s;
 }
 .fa-instagram:hover{
  color:#ecb365;
  transition: ease 1s;
 }
</style>