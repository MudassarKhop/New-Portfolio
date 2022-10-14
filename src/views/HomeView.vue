<template>
<section id="homepage">
  <div id="socials">
    <a href="">    <i class="fa-brands fa-github"></i>
</a><a href="">    <i class="fa-brands fa-linkedin"></i>
</a><a href="">    <i class="fa-brands fa-twitter"></i>
</a>
<a href=""><i class="fa-brands fa-instagram"></i></a>
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
</section>
<section id="about">
<div id="about1"></div>
<div id="about2">
  <div id="heading">
    <h1>about me</h1>
    <h5>20 years young / cape town / intern</h5>
  </div>
  <div id="passage">
    <p>I'm an ambitious, focused and determined individual. I'm also very
							competitive. I always look for ways to challenge myself. I'm very
							patient with others and work well in a team environment. I have a
							very spontaneous personality, which makes me think the adventurous
							characteristic applies to me. I have always been fascinated with
							technology, and I hope to become a web and or software developer.</p>
  </div>
  <div id="skillsblocks">
    <div id="skills">
      <div id="heading">
        <h5><i class="fa-solid fa-people-group"></i> Team Player</h5>
        <p style="text-align:start; color:rgba(255, 255, 255, 0.686); font-size:18px">In my time playing football, I realised that the team can only succeed working as one unit.</p>
      </div>
    </div>
    <div id="skills">
      <div id="heading">
        <h5><i class="fa-solid fa-bolt"></i> Determination</h5>
        <p style="text-align:start; color:rgba(255, 255, 255, 0.686); font-size:18px">Once commited to a task, I strive to do to everything in my power to complete the task. </p>
      </div>
    </div>
    <div id="skills">
      <div id="heading">
        <h5><i class="fa-solid fa-brain"></i> Problem Solving</h5>
        <p style="text-align:start; color:rgba(255, 255, 255, 0.686); font-size:18px">In the academy where I learn't coding, I faced many obstacles but when put under pressure, I produce some of my best work.</p>
      </div>
    </div>
    <div id="skills">
      <div id="heading">
        <h5><i class="fa-solid fa-stairs"></i> Leadership</h5>
        <p style="text-align:start; color:rgba(255, 255, 255, 0.686); font-size:18px">I believe I possess some of the core skills to be a leader such as, time management, flexbility, creativity and most importantly postivity. </p>
      </div>
    </div>
  </div>
</div>
</section>
<section id="projects">

</section>
<section id="testimonials">

</section>
<section id="contact">

</section>
</template>

<script>
</script>
<style>
/* homepage */
 #homepage{
  height: 101vh;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-content: center;
  border-bottom: 1px solid #04293a;
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
background-color: #064663;
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
    animation-duration: 3s;
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
 /* homepage */
 /* about */
 #about{
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-content: center;
  height: 80vh;
  border-bottom: 1px solid #04293a;

 }
 #about1{
  width: 65%;
  height: 100%; 
  /* border: 3px solid gresen; */
 }
 #about2{
  background-color: #064663;
  width: 35%;
  height: 100%;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: start;
  align-content: flex-start;
  /* border: 3px solid green; */
 }
 #heading{
  width: 100%;
  color: white;
  display: flex;
  flex-direction: column;
  flex-wrap: nowrap;
  justify-items: start;
  align-items: flex-start;
  padding: 20px;
  letter-spacing: 2px;
 }
  h5{
  color: #ecb365;
 }
 #passage{
  display: flex;
  flex-direction: column;
  flex-wrap: nowrap;
  justify-content:center;
  align-content: center;
  /* background-color: ; */
  width: 80%;
  padding: 10px;
  /* border-bottom: 1px solid #04293a; */
  /* box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px; */
 }
 #passage p{
  color: rgba(255, 255, 255, 0.686);
  text-align: start;
  font-size: 18px;
  letter-spacing: 1px;
  padding-left: 13px;
  padding-bottom: 13px;

 }
#skillsblocks{
  /* border: 3px solid red; */
  width: 100%;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-content: center;
}
#skills{
  width: 50%;
  /* border: 3px solid green; */
  height: 200px;
}
#skills h5{
color: white;
}
.fa-people-group{
  color: #ecb365;
}
.fa-bolt{
  color: #ecb365;
}
.fa-brain{
  color:#ecb365;
}
.fa-stairs{
  color: #ecb365;
}
 /* about */
 /* projects */
 #projects{
  height: 100vh;
 }
 /* projects */
 /* testimonials */
 #testimonials{
  height: 100vh;

 }
 /* testimonials */
 /* contact */
 #contact{
  height: 100vh;
 }
 /* contact */
</style>
