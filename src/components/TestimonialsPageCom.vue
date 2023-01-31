<template >
    <div id="heading">
        <h1>testimonials</h1>
        <h5>what people say about me and my work</h5>
    </div>
    <div id="testimonial">
        <div class="micro-slider-wrapper">
     <div id="nextt" class="nextt"><i class="fa fa-angle-right" aria-hidden="true"></i></div>
     <div class="micro-slider">
        <div class="slider-item s1">
             <div class="slider-card">
                <img loading="lazy" src="https://i.postimg.cc/Qx94pNhP/T02-LW4-RMXJQ-U036-JA3-NVL5-45897a34dc43-512-1.jpg" class="course_image">
                <div class="overlay"></div>
                <div class="slider-item-info">
                <div class="slider-item-description">
                   <div>
                        Mudassar shows a lot of promise as a software developer. I'm happy seeing Mudassar grow as a developer, I hope he continues to work hard.
                   </div>
                </div>
              <div class="course-title">-Jason Wandrag</div>
                <div class="course-title2">lecturer</div>
                </div>            
             </div>
          </div>
          <div class="slider-item s2">
             <div class="slider-card">
                <img loading="lazy" src="https://i.postimg.cc/02XhPJjz/Optimized-Carla-1.jpg" class="course_image">
                                <div class="overlay"></div>

                <div class="slider-item-info">
                <div class="slider-item-description">
                   <div>
                    Mudassar is a highly competent, focused web developer. His friendly disposition draws his colleagues to him, he is impressionable to everyone he comes in contact with.                   </div>
                </div>
                <div class="course-title">-Carla Amy Lawrence</div>
                <div class="course-title2">peer</div>
                </div>            
             </div>
          </div>
          <div class="slider-item s3">
             <div class="slider-card">
                <img loading="lazy" src="https://i.postimg.cc/D0MnbpvG/Optimized-Jesse-2.jpg" class="course_image">
                                <div class="overlay"></div>

                <div class="slider-item-info">
                <div class="slider-item-description">
                   <div>
                    It is my great pleasure to have worked with Mudassar Khopatkar as he is a good team worker.He can collaborate and communicate with others on their ideas.
                   </div>
                </div>
                 <div class="course-title">-Jesse Spence</div>
                <div class="course-title2">peer</div>
                </div>            
             </div>
          </div>
          <div class="slider-item s4">
             <div class="slider-card">
                <img loading="lazy" src="https://i.postimg.cc/sXTSLW9c/Optimized-Ricardo-2.jpg" class="course_image">
                                <div class="overlay"></div>

                <div class="slider-item-info">
                <div class="slider-item-description">
                   <div>
                    Mudassar is a committed ,ambitious and competitive person. He is a great colleague who always encourages me to do my best.
                   </div>
                </div>
                <div class="course-title">-Ricardo Moses</div>
                <div class="course-title2">peer</div>
                </div>            
             </div>
          </div>

          <div class="slider-item s5">
             <div class="slider-card">
                <img loading="lazy" src="https://i.postimg.cc/BbktGn1R/Optimized-Tshimologo-2.jpg" class="course_image">
                                <div class="overlay"></div>

                <div class="slider-item-info">
                <div class="slider-item-description">
                   <div>
                       I'm profoundly impressed with Mudassar's attitude towards his work, his work ethics shows in his projects. He works very well in a team from experiences.
                   </div>
                </div>
               <div class="course-title">-Tsimilogo King</div>
                <div class="course-title2">peer</div>
                </div>            
             </div>
          </div>   
    </div>
    <div id="prevv" class="prevv"><i class="fa fa-angle-left" aria-hidden="true"></i></div>
</div>
 </div>
</template>
<script>
    import Hammer from 'hammerjs'
    import MicroSlider from 'micro-slider';

export default {
     created() {
         const indicators = document.querySelector('ul.indicators');
         console.log(indicators)
         setTimeout( () => {
            const slider1 = document.querySelector('.slider-wrapper');
        slider1.style.removeProperty('height')
        slider1.style.removeProperty('overflow')
        slider1.style.removeProperty('perspective')
        slider1.style.perspective = '1500px'
        slider1.style.height = '730px'
        indicators.style.display = 'none'
     
}, 1000);
this.Slider()
   
    },

    methods: {

        Slider() {
            document.addEventListener('DOMContentLoaded', () => {
                console.log('slider working')
  
  const __ms = document.querySelector('.micro-slider');
  
  const __msSlider = new MicroSlider(__ms, {});
  
  const hammer = new Hammer(__ms);
  
  const __msTimer = 3000;
  
  let __msAutoplay = setInterval(() => __msSlider.next(), __msTimer);
    

   __ms.onmouseenter = function(e) {
    clearInterval(__msAutoplay); 
    console.log(e.type + ' mouse detected');
  }


   __ms.onmouseleave = function(e) {

        clearInterval(__msAutoplay);

        __msAutoplay = setInterval(() => __msSlider.next(), __msTimer);

        console.log(e.type + ' mouse detected');

    }
  
__ms.onclick = function(e) {
  clearInterval(__msAutoplay);
  console.log(e.type + ' mouse detected');
}
  
hammer.on('tap', function(e) {
  clearInterval(__msAutoplay);
  console.log(e.type + ' gesture detected');
});
  
  
hammer.on('swipe', function(e) {
  clearInterval(__msAutoplay);
  __msAutoplay = setInterval(() => __msSlider.next(), __msTimer);
  console.log(e.type + ' gesture detected');
});

document.getElementById("nextt").addEventListener('click', (e) => {
   e.preventDefault();
   __msSlider.next();
});

document.getElementById("prevv").addEventListener('click', (e) => {
   e.preventDefault();
   __msSlider.prev();
});
});
        }

    }
}  
</script>

<style scoped>
#heading {
    width: 88%;
    height: 10%;
    display: flex;
    flex-direction: column;
    flex-wrap: nowrap;
    justify-content: start;
    align-items: flex-end;
}

#heading h1 {
    color: white;
    text-align: left;
    letter-spacing: 2px;

}

#heading h5 {
    color: #ecb365;
    text-align: left;
    letter-spacing: 1px;
}

#testimonial {
    height: 70%;
    width: 100%;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: center;
    align-items: flex-start;
    gap: 20px;
}

#test {
    width: 44%;
    height: 32%;
    background-color: #04293a;
    border-radius: 12px;
    box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px, rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px, rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;
}


div,
a {
    font-family: Pro;
    letter-spacing: 2px;
    font-size: 19px;
}

.nextt {
    font-size: 35px;
    position: absolute;
    right: 10%;
    background: #04293a;
    width: 50px;
    height: 50px;
    border-radius: 50%;
    text-align: center;
    color: #ecb365;
    cursor: pointer;
    z-index: 1;
    margin-top: 300px;
}
ul.indicators {
    display: none !important;
}
.prevv {
    font-size: 35px;
    position: absolute;
    left: 10%;
    background: #04293a;
    width: 50px;
    height: 50px;
    border-radius: 50%;
    text-align: center;
    color: #ecb365;
    cursor: pointer;
    margin-top: 300px;
}

#nextt .fa {
    margin-top: 7px;
    margin-left: 3px;
}

#prevv .fa {
    margin-top: 7px;
    margin-left: -3px;
}

.nextt:hover {
    background: #ecb365;
    color: #04293a;
    -webkit-box-shadow: 1px 1px 10px 0px rgba(0, 0, 0, 0.3);
    -moz-box-shadow: 1px 1px 10px 0px rgba(0, 0, 0, 0.3);
    box-shadow: 1px 1px 10px 0px rgba(0, 0, 0, 0.3);
}

.prevv:hover {
    background: #ecb365;
    color: #04293a;
    -webkit-box-shadow: 1px 1px 10px 0px rgba(0, 0, 0, 0.3);
    -moz-box-shadow: 1px 1px 10px 0px rgba(0, 0, 0, 0.3);
    box-shadow: 1px 1px 10px 0px rgba(0, 0, 0, 0.3);
}

.micro-slider-wrapper {
    display: flex;
    width: 100%;
}

.slider-item-info {
    padding: 25px;
    height: 300px;
    width: 500px !important;
    background-color: #04293a;
border-bottom-left-radius: 20px;
border-bottom-right-radius: 20px;

}
.slider-item-description {
    height: 53%;
    text-align: center;
    margin-top: 15px;
    margin-bottom: 20px;
    font-size: 19px;
    color: rgba(255, 255, 255, 0.686);
}

.course_image {
    aspect-ratio: 1/2;
    object-fit: cover;
    height: 350px;
    width: 100%;
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
    
}

.course-title {
    font-size: 25px;
    letter-spacing: 2px;
    color: #ecb365;
    font-weight: 300;
    /*color: #4b4bff;*/
    text-align: right;
}
.course-title2 {
    font-size: 22px;
    letter-spacing: 2px;
    color: white;
    font-weight: 100;
    /*color: #4b4bff;*/
    text-align: right;
}



.micro-slider {
    height: 710px;
    position: relative;
    width: 100%;
}

.slider-item {
    box-shadow: 0 1px 3px rgba(0, 0, 0), 0 1px 2px rgba(0, 0, 0);
    height: auto !important;
    width: 370px;
    left: 0;
    position: absolute;
    border-radius: 20px;
}

.s1,
.s2,
.s3,
.s4,
.s5,
.s6 {
    background: #04293a;
    color: white;
    box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px, rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px, rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;
}

.micro-slider ul{
    display: none;
}

.slider-card {
    width: 500px !important;
    height: 600px;
}


@media screen and (max-width: 1400px) {
    .nextt {
        top: 0%;
        right: 0%;
    }

    .prevv {
        top: 0%;
        left: 0%;
    }
}

@media screen and (max-width: 480px) {
    .slider-item {
        width: 90% !important;
    }
}
.overlay {
    position: absolute;
  top: 210px;
  height: 141px;
		background-image: -webkit-linear-gradient(
			top,
			transparent 0%,
			#ffffff 100%
		);
		background-image: linear-gradient(to bottom, transparent 0%, #04293a 100%);
  width: 500px;
  transition: .5s ease;
  opacity:0;
  color: white;
  font-size: 20px;
  padding: 20px;
  text-align: center;
  opacity: 1;
}
@media only screen and (max-width: 600px) and (min-width: 389px) {
    #testimonial{
        display: none;
    }
}
</style>