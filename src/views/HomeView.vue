<template>
<section id="homepage">
<HomePageCom />
</section>
<section id="about">
<AboutPageCom />
</section>
<section id="projects">
<StackPageCom />
</section>
<section id="work">
<WorkPageCom />
</section>
<section id="testimonials">
  <TestimonialsPageCom />
</section>
<section id="contact">
 <ContactPageCom />
</section>
<section id="footer">
  <div>
    <h5>©2022-present | all-rights-reserved</h5>
  </div>
</section>
</template>

<script>
import HomePageCom from '../components/HomePageCom.vue';
import AboutPageCom from '../components/AboutPageCom.vue';
import StackPageCom from '../components/StackPageCom.vue';
import TestimonialsPageCom from '../components/TestimonialsPageCom.vue';
import ContactPageCom from '../components/ContactPageCom.vue';
import WorkPageCom from '../components/WorkPageCom.vue';
export default {
  components: {
    HomePageCom, AboutPageCom, StackPageCom, TestimonialsPageCom, ContactPageCom, WorkPageCom
  }
}
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
 }
 /* homepage */
 /* about */
 #about{
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-content: center;
  height: 100vh;

 }
/* about */
 /* projects */
 #projects{
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-content: center;
  height: 100vh;
  gap: 2%;
 }
  /* projects */
  /* work */
  #work{
    height: 100vh;
    display: flex;
    flex-direction: column;
    flex-wrap: nowrap;
    justify-content: center;
    align-items: center;
  }
  /* work */
 /* testimonials */
 #testimonials{
  height: 100vh;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-content: center;
 }
 /* testimonials */
 /* contact */
 #contact{
  height: 95vh;
  display: flex !important;
  flex-direction: row !important;
  flex-wrap: wrap !important;
  justify-content: center !important;
  align-items: center !important;
 }
  /* contact */
 #footer{
  height: 5vh;
  background-color: #04293a;
 }
 #footer h5{
  font-size: 16px;
  text-align: center;
  color: rgba(223, 223, 223, 0.695);
 }
 #footer div{
  display: flex !important;
  flex-direction: row !important;
  flex-wrap: nowrap !important;
  justify-content: start !important;
  align-items: center !important;
  width: 50%;
  height: 100%;
  padding-left: 20px;
  padding-top: 15px;
 }
 @media only screen and (max-width: 600px) and (min-width: 389px) {
  #footer div{
    width: 100%;
  }
  #footer h5{
    font-size: 13px;
  }
  #homepage{
flex-direction: column;
min-height: 100vh;
  }
  #about{
    display: flex;
    flex-wrap:wrap ;
    flex-direction: column;
    min-height: 100vh;
  }
  #projects{
    flex-direction: column;
    min-height: 100vh;
  }
  #work{
flex-direction: column;
min-height: 100vh;
  }
  #testimonials{
flex-direction: column;
min-height: 100vh;
  }
  #contact{
    flex-direction: column;
    min-height: 95vh;
  }
}
</style>
