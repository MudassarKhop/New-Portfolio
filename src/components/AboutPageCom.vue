<template>
  <div id="about2" >
  <div id="heading">
    <h1>about me</h1>
    <h5>20 years young <span>/</span> cape town <span>/</span> intern</h5>
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
        <p class="traits" style="text-align:end; color:rgba(255, 255, 255, 0.686); font-size:18px">In my time playing football, I realised that the team can only succeed working as one unit.</p>
      </div>
    </div>
    <div id="skills">
      <div id="heading">
        <h5><i class="fa-solid fa-bolt"></i> Determination</h5>
        <p class="traits" style="text-align:end; color:rgba(255, 255, 255, 0.686); font-size:18px">Once commited to a task, I strive to do to everything in my power to complete the task. </p>
      </div>
    </div>
    <div id="skills">
      <div id="heading">
        <h5><i class="fa-solid fa-brain"></i> Problem Solving</h5>
        <p class="traits" style="text-align:end; color:rgba(255, 255, 255, 0.686); font-size:18px">In the academy where I learnt coding, I faced many obstacles but when put under pressure, I produce some of my best work.</p>
      </div>
    </div>
    <div id="skills">
      <div id="heading">
        <h5><i class="fa-solid fa-stairs"></i> Leadership</h5>
        <p class="traits" style="text-align:end; color:rgba(255, 255, 255, 0.686); font-size:18px">I believe I possess some of the core skills to be a leader such as: time management, flexbility, creativity and most importantly postivity. </p>
      </div>
    </div>
  </div>
</div>
<div id="about1">
  <div class="container2">
			<div class="box">
				<div class="imgBx">
					<img src="https://i.postimg.cc/gjkPfPs5/IMG-20221016-WA0053.jpg" />
				</div>
					<div class="content">
						<div>
							<h2>Hiking</h2>
							<p>
								My adventurous personality follows me climbing some of the most beautiful mountains in Cape Town.
							</p>
						</div>
					</div>
			</div>
			<div class="box">
				<div class="imgBx">
					<img
						src="https://i.postimg.cc/C100s8qw/20220131-205308.jpg"
					/>
				</div>
        <div class="content">
						<div>
							<h2>ME</h2>
							<p>
								Driven, determined, focused and competitive but you already know that. Why don't you have a look at some of my projects below.
							</p>
						</div>
					</div>
			</div>
			<div class="box">
				<div class="imgBx">
					<img src="https://i.postimg.cc/wvkpfBXL/IMG-20220617-WA0027.jpg" />
				</div>
					<div class="content">
						<div>
							<h2>Fives Football</h2>
							<p>
								Besides my strong passion for coding and technology, I play football to escape from the real world for 60 minutes. To restart my thinking system and return with new ideas.
							</p>
						</div>
					</div>
			</div>
		</div>
</div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
span{
	color: white;
}
     #about{
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-content: center;
  height: 100vh;

 }
 #about1{
  width: 62%;
  height: 100%; 
  /* border: 3px solid gresen; */
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-content: center;
 }
 #about2{
  /* background-color: #064663; */
  width: 38%;
  height: 100%;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: end;
  align-content: center;
  /* border: 3px solid green; */
 }
 #heading{
  width: 100%;
  color: white;
  display: flex;
  flex-direction: column;
  flex-wrap: nowrap;
  justify-items: end;
  align-items: flex-end;
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
  justify-items:center;
  align-content: center;
  /* background-color: ; */
  width: 80%;
  padding: 10px;
  /* border-bottom: 1px solid #04293a; */
  /* box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px; */
 }
 #passage p{
  color: rgba(255, 255, 255, 0.686);
  text-align: end;
  font-size: 20px;
  letter-spacing: 1px;
  padding-left: 13px;
  padding-bottom: 13px;
}
#skillsblocks{
  /* border: 3px solid red; */
  width: 93%;
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
		margin-top: 45px;
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
		box-shadow: rgb(159 143 79 / 56%) 0px 22px 70px 4px;	}
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
		background: linear-gradient(180deg, rgb(11, 18, 84), #000);
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
		font-family: Pro;
		color: #ecb365;
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
		font-family: Pro;
		color: #fff;
		transition: 0.5s;
		font-size: 14px;
    letter-spacing: 2px;
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
	}
	@media only screen and (max-width: 600px) and (min-width: 389px){
		.container2 .box[data-v-0c05a456] {
    min-width: 330px;
    margin-right: none;
	min-height: 530px;
}
.container2:hover .box {
		transform: none;
	}
	.container2 .box:hover ~ .box {
		transform: none;
	}
	.container2 .box:hover {
		transform: none;
		z-index: 1;
		box-shadow: none;	
	}
.container2 {
			gap: 30px;
		}
#heading{
	justify-items: center;
    align-items: center;
}
#heading h1{
	font-size: 25px;
}
#heading h5{
	font-size: 15px;
}
#passage{
	width: 100%;
}
#passage p{
	text-align: center;
	padding-bottom: 0 !important;
	padding-left: 0 !important;
	margin-bottom: 0 !important;
}
#skillsblocks{
	display: flex;
	flex-wrap: nowrap;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	width: 100%;
}
#skills{
	width: 100%;
	height: 160px;
}
.traits{
	text-align: center !important;
	font-size: 17px !important;
}
#about2{
	width: 100%;
}
#about1{
	width: 100%;
}

	}
</style>