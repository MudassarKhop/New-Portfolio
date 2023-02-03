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
<h1>I'M <span>MUDASSAR KHOPATKAR</span>;</h1>
<h2>ASPIRING <span>WEB-DEVELOPER</span></h2>
<div id="buttons">
  <button id="b1"><a href="https://resume.io/r/WKoqcPhh8" target="_blank">RESUME</a></button>
  <button id="b2"> <a href="#contact">CONTACT ME</a></button>
</div>
<div class="png2">
  <img id="png2" src="https://i.postimg.cc/VNmx3t74/image.png" alt="">
</div>
</div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
a{
  text-decoration: none;
  color: white;
  transition: 0.1s ease-in;

}
a:hover{
  transition: 0.1s ease-in;
color: rgba(255, 255, 255, 0.87);
}
     #homepage{
  height: 100vh;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: start !important;
  align-items: center !important;
 }
 #title{
  /* border: 3px solid red; */
  height: 100%;
  width:85%;
  text-align: start;
  color: white;
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  justify-content: center;
  align-content: flex-start;
  
 }
 #title h3{
  font-size: 45px;
  letter-spacing: 2px;
  color: rgb(223, 223, 223);
  text-shadow: 0 5px 5px black;
  font-weight:500 ;
 }
 #title h1{
  font-size: 85px;
  letter-spacing: 4px;
  color: rgb(223, 223, 223);
  text-shadow: 0 5px 5px black;
  font-weight: 700;
  }
   #title h2{
  font-size: 30px;
  letter-spacing: 2px;
  color: rgb(223, 223, 223);
  text-shadow: 0 5px 5px black;
  font-weight: 500 ;
  margin-bottom: 0;
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
    box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px, rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px, rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;
  text-shadow: 0 4px 4px black;
  transition: 0.2s ease-in;

 }  
 button:hover{
  transition: 0.2s ease-in;
  color: rgba(255, 255, 255, 0.87);

 }
 #b1{
  background-color: #c69653;
 }
 #b1:hover{
  background-color: #c69653ae;
  box-shadow: none;
 }
 #b2{
background-color: #0b3447;
 }
 #b2:hover{
  background-color: #0b34478e;
        box-shadow: none;
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
 @media only screen and (max-width: 600px) and (min-width: 389px) {
  #socials{
    display: none;
  }
  #title h1{
  font-size: 54px;
  letter-spacing: 4px;
  color: rgb(223, 223, 223);
  text-shadow: 0 5px 5px black;
  font-weight: 700;
  }
  #homepage{
    flex-direction: column;
  }

}
</style>