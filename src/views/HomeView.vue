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
<div id="about1">
  <div class="container2">
			<div class="box">
				<div class="imgBx">
					<img src="https://i.postimg.cc/tCrQqqCt/1431931.jpg" />
				</div>
				<router-link to="/flights">
					<div class="content">
						<div>
							<h2>Indonesia, Bali</h2>
							<p>
								Bali has the world's most expensive coffee. The most expensive
								coffee in the world comes from poop.
							</p>
						</div>
					</div>
				</router-link>
			</div>
			<div class="box">
				<div class="imgBx">
					<img
						src="https://i.postimg.cc/2j2XvHRC/eiffel-tower-paris-4k-wide-1536x864.jpg"
					/>
				</div>
				<router-link to="/flights">
					<div class="content">
						<div>
							<h2>France, Paris</h2>
							<p>Paris was originally a Roman City called “Lutetia.”</p>
						</div>
					</div>
				</router-link>
			</div>
			<div class="box">
				<div class="imgBx">
					<img src="https://i.postimg.cc/DZm4NyZj/2338846.jpg" />
				</div>
				<router-link to="/flights">
					<div class="content">
						<div>
							<h2>Monaco</h2>
							<p>
								Monaco is the 2nd smallest country in the world, a “microstate”
								(or city-state) of only 2 sq km.
							</p>
						</div>
					</div>
				</router-link>
			</div>
		</div>
</div>
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
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-content: center;
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
#pictures1{
width: 25%;
height:100%;
border:3px solid red;
 display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-content: center;
}
#pictures2{
  width: 40%;
height:100%;
border: 3px solid green;
 display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-content: center;
}
#pictures3{
width: 25%;
height:100%;
border:3px solid red;
 display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-content: center;
}
.container2 {
		position: relative;
		margin-left: 20px;
		width: 100%;
		display: flex;
		justify-content: center;
		flex-wrap: wrap;
		transform-style: preserve-3d;
		perspective: 500px;
		padding: 2%;
	}
	.container2 .box {
		/* position: relative; */
		min-width: 325px;
		min-height: 700px;
		background: #000;
		transition: 0.5s;
		transform-style: preserve-3d;
		overflow: hidden;
		margin-right: 20px;
	}
	.container2:hover .box {
		transform: rotateY(25deg);
	}
	.container2 .box:hover ~ .box {
		transform: rotateY(-25deg);
	}
	.container2 .box:hover {
		transform: rotateY(0deg) scale(1.25);
		z-index: 1;
		box-shadow: 0 25px 40px rgba(0, 0, 0, 0.5);
	}
	.container2 .box .imgBx {
		position: absolute;
		top: 0;
		left: 0;
		width: 100%;
		height: 100%;
	}
	.container2 .box .imgBx:before {
		content: "";
		position: absolute;
		top: 0;
		left: 0;
		width: 100%;
		height: 100%;
		background: linear-gradient(180deg, black, #000);
		z-index: 1;
		opacity: 0;
		transition: 0.5s;
		mix-blend-mode: multiply;
	}
	.container2 .box:hover .imgBx:before {
		opacity: 1;
	}
	.container2 .box .imgBx img {
		position: absolute;
		top: 0;
		left: 0;
		width: 100%;
		height: 100%;
		object-fit: cover;
	}
	.container2 .box .content {
		position: absolute;
		top: 0;
		left: 0;
		width: 100%;
		height: 100%;
		z-index: 1;
		display: flex;
		padding: 20px;
		align-items: flex-end;
		box-sizing: border-box;
	}
	.container2 .box .content h2 {
		font-family: Von;
		color: #fff;
		transition: 0.5s;
		text-transform: uppercase;
		margin-bottom: 5px;
		font-size: 20px;
		transform: translateY(200px);
		transition-delay: 0.3s;
	}
	.container2 .box:hover .content h2 {
		transform: translateY(0px);
	}
	.container2 .box .content p {
		font-family: Verdana, Geneva, Tahoma, sans-serif;
		color: #fff;
		transition: 0.5s;
		font-size: 14px;
		transform: translateY(200px);
		transition-delay: 0.4s;
	}
	.container2 .box:hover .content p {
		transform: translateY(0px);
	}
	/* informations cards */
	@media only screen and (max-width: 1315px) {
		#home img {
			display: none;
		}
		#home h1 {
			text-align: center;
			font-size: 40px;
		}
		#card1 {
			display: flex;
			flex-direction: column;
			flex-wrap: nowrap;
			min-width: 20%;
		}
		#card2 {
			display: flex;
			flex-direction: column;
			flex-wrap: nowrap;
			min-width: 70%;
		}
		#divide1 {
			min-height: 500px;
			min-width: 100%;
		}
		#divide1 p {
			padding: 20px;
			text-align: center;
		}
		#divide2 {
			min-height: 50%;
			min-width: 100%;
		}
		#stuuf {
			min-height: 100%;
		}
		.stuff1 {
			display: flex;
			flex-direction: column;
			flex-wrap: wrap;
		}
		.stuff2 {
			display: flex;
			flex-direction: column;
			flex-wrap: wrap;
		}
		#divide4 {
			min-height: 500px;
			min-width: 100%;
		}
		#card11 {
			display: flex;
			flex-direction: column;
			flex-wrap: nowrap;
			min-width: 70%;
		}
		#card11 h1 {
			margin-top: 30px;
			margin-bottom: 30px;
		}
		#card11 p {
			padding: 50px;
		}
		#card22 {
			display: flex;
			flex-direction: column;
			flex-wrap: nowrap;
			min-width: 70%;
		}
		.container2 {
			gap: 10px;
			margin-bottom: 20px;
			margin-top: 20px;
		}
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
