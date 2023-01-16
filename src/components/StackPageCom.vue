<template >
  <div id="stack">
  <div  id="heading2">
    <h1>my stack</h1>
    <h5>my current skills set</h5>
  </div>
  <div id="languages">
    <div>    <i  class="fa-brands fa-html5"  data-bs-toggle="tooltip" data-bs-title="Default tooltip"></i>
</div>
    <div>    <i  class="fa-brands fa-css3-alt"></i>
</div>
    <div>    <i  class="fa-brands fa-bootstrap"></i>
</div>
    <div>    <i  class="fa-brands fa-square-js"></i>
</div>
    <div>
    <i class="fa-brands fa-vuejs"></i></div>
    <div>
      <i class="fa-brands fa-node-js"></i></div>
    <div>
      <i class="fa-brands fa-php"></i></div>
    <div>
      <i class="fa-brands fa-node"></i></div>
    <div>    <i class="fa-brands fa-wordpress"></i>
</div>
  </div>
</div>
<div id="projectss">
  <!-- <div  id="heading3">
    <h1>my journey</h1>
    <h5>how i achieved my goals</h5>
  </div> -->
  <div id="journey">
    <div id="j1">
      <img style="height:300px; width:200px" src="https://i.postimg.cc/sfBjRZ7G/kindpng-567305-removebg-preview.png" alt="">
<div style="text-align:start" id="jhead"><h2>schooling</h2><h4>2016-2021</h4>
<p>In the period of 2016-2021, I attended Rylands High School in the Athlone area. During this period I failed Grade 11 once and I'd like to believe this was the turning point in my life that motivated me to work harder to achieve my dream career in coding. </p></div>
    </div>
    <div id="j2">
      <div style="text-align:end" id="jhead"><h2>coding</h2><h4>2022-2023</h4>
     <p>I learnt how to code at <span>Life Choices Academy</span> in the bootcamp from March-September. This opportunity was handed to me by highschool <span>math teacher</span> who saw the potential within me. This is where I picked up my stack on the left under some of the best lecturers.</p></div>
      <img style="height:310px; width:300px" src="https://i.postimg.cc/Qd3tJkVZ/d-funny-character-cartoon-sympathetic-looking-business-man-dear-person-suit-glasses-tie-47992402-tra.png" alt="">
    </div>
    <div id="j3">
      <img style="height:300px; width:290px" src="https://i.postimg.cc/Sx6Ggrr6/d-funny-character-cartoon-sympathetic-looking-business-man-dear-person-suit-glasses-tie-47992420-tra.png" alt="">
   <div style="text-align:start" id="jhead"><h2>interning</h2><h4>Sep 2022-Dec 2022</h4>
  <p>I interned at <span>New Grizzly Marketing Amsterdam</span>, where I further improved my skillset through <span>WordPress</span> and <span>Google SEO's</span>.</p></div>
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
  text-shadow: none;
  letter-spacing: 1px;
}
    #projects{
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-content: center;
  height: 100vh;
  gap: 4%;
 }
 #stack{
  width: 42%;
  height: 100%;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-content: center;
  /* border: 3px solid white; */
 }
 #heading2{
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
 #heading2 h5{
    color: #ecb365;
 }
 #heading3{
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
#languages{
  width: 100%;
  height: 65%;
  /* border: 3px solid green; */
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: end;
  align-content: flex-end;
  gap: 20px;

}
#languages div{
  background-color:#04293a ;
  width: 225px;
  height: 210px;
  border-radius: 12px;
  box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px, rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px, rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;

}
     .fa-html5{
      font-size:100px ;
      color: white;
      padding: 50px;
      }  
     .fa-css3-alt{
      font-size:100px ;
      color: white;
      padding: 50px;
     }
     .fa-bootstrap{
      font-size:100px ;
      color: white;
      padding: 50px;
     }
     .fa-square-js{
      font-size:100px ;
      color: white;
      padding: 50px;
     }
     .fa-vuejs{
      font-size:100px ;
      color: white;
      padding: 50px;
     }
     .fa-php{
      font-size:100px ;
      color: white;
      padding: 50px;
     }
     .fa-node-js{
      font-size:100px ;
      color: white;
      padding: 50px;
     }
     .fa-node{
      font-size:100px ;
      color: white;
      padding: 50px;
      transition: 0.6s ease-in;
     }
     .fa-wordpress{
      font-size:100px ;
      color: white;
      padding: 50px;
     }

     .fa-github:hover{
      color: #ecb365;
      } 
      .fa-node:hover{
      color: #ecb365;
      } 
      .fa-node-js:hover{
      color: #ecb365;
      } 
      .fa-php:hover{
      color: #ecb365;
      transition: 0.6s ease-in;

      } 
      .fa-html5:hover{
      color: #ecb365;
      } 
     .fa-css3-alt:hover{
      color: #ecb365;
     }
     .fa-bootstrap:hover{
      color: #ecb365;
     }
     .fa-square-js:hover{
      color: #ecb365;
     }
     .fa-vuejs:hover{
      color: #ecb365;
     }
     .fa-wordpress:hover{
     color: #ecb365;
     }
     #projectss{
      margin-top: 35px;
      width: 50%;
      height: 100%;
      display: flex;
      flex-direction: row;
      flex-wrap: wrap;
      justify-content: center;
      align-content: center;
      /* border: 3px solid red; */

     }
     #procard{
      width: 100%;
  /* border: 3px solid green; */
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: start;
  align-content: flex-start;
  gap: 20px;
     }
     #cards{
      width: 249px;
      height: 400px;
      box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px, rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px, rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;

      background-color: #04293a;
     }
     #imgcon{
      width: 100%;
      height: 40%;
     }
     #proimg{
      width: 100%;
      height: 100%;
      aspect-ratio: 1;
     }
     #titlepro{
      width: 100%;
      height: 35%;
      /* border: 2px solid yellow; */
      display: flex !important;
      flex-direction: column !important;
      flex-wrap: nowrap !important;
      justify-content: center !important;
      align-items: center !important;
     }
     #titlepro h1{
      font-size: 23px;
      letter-spacing: 1px;
      color: white;
      /* margin-bottom: 0 !important; */
     }
     #titlepro h5{
      font-size: 17px;
      letter-spacing: 1px;
      /* margin-bottom: 0 !important; */
     }
     .btn{
      width: 80%;
      height: 50%;
      background-color: #ecb365;
      border: none;
      display: flex !important;
      flex-direction: row !important;
      flex-wrap: nowrap !important;
      justify-content: center !important;
      align-items: center !important;
     }
     .btn h5{
      color: white;
      font-size: 20px;
      /* padding-top: 17px;
      padding-bottom: 17px; */
     }
     #journey{
      width: 80%;
      height: 70%;
      display: flex !important;
      flex-direction: column !important;
      flex-wrap: nowrap !important;
      justify-content: center !important;
      align-items: center !important;
     }
     #j1{
      width: 100%;
            display: flex !important;
      flex-direction: row !important;
      flex-wrap: nowrap !important;
      justify-content: start !important;
      align-items: center !important;
      transition: 0.2s ease-in;
      padding: 5px;


     }
     #j2{
      width: 100%;
            display: flex !important;
      flex-direction: row !important;
      flex-wrap: nowrap !important;
      justify-content: end !important;
      align-items: center !important;
      transition: 0.2s ease-in;
      padding: 5px;

     }
     #j3{
      width: 100%;
      display: flex !important;
      flex-direction: row !important;
      flex-wrap: nowrap !important;
      justify-content: start !important;
      align-items: center !important;
      transition: 0.2s ease-in;
      padding: 5px;


     }
     #jhead h2{
      color: white;
      letter-spacing: 1px;
     }
     #jhead h4{
      color: #ecb365;
  text-shadow: none;
  letter-spacing: 1px;
     }
     #jhead p{
      color: rgba(255, 255, 255, 0.686);
      font-size: 20px;
      letter-spacing: 1px;
     }
</style>