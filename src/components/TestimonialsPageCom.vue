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
                <img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80" class="course_image">
                <div class="slider-item-info">
                <div class="course-title">Carla Amy Lawrence</div>
                <div class="course-title2">peer</div>
                <div class="slider-item-description">
                   <div>
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
                   </div>
                </div>
                </div>            
             </div>
          </div>
          <div class="slider-item s2">
             <div class="slider-card">
                <img src="https://images.unsplash.com/photo-1476514525535-07fb3b4ae5f1?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80" class="course_image">
                <div class="slider-item-info">
                <div class="course-title">Jason Wandrag</div>
                <div class="course-title2">lecturer</div>
                <div class="slider-item-description">
                   <div>
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
                   </div>
                </div>
                </div>            
             </div>
          </div>
          <div class="slider-item s3">
             <div class="slider-card">
                <img src="https://images.unsplash.com/photo-1542744173-8e7e53415bb0?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80" class="course_image">
                <div class="slider-item-info">
                <div class="course-title">Jesse Spence</div>
                <div class="course-title2">peer</div>
                <div class="slider-item-description">
                   <div>
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
                   </div>
                </div>
                </div>            
             </div>
          </div>
          <div class="slider-item s4">
             <div class="slider-card">
                <img src="https://images.unsplash.com/photo-1572025442646-866d16c84a54?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80" class="course_image">
                <div class="slider-item-info">
                <div class="course-title">Ricardo Moses</div>
                <div class="course-title2">peer</div>
                <div class="slider-item-description">
                   <div>
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
                   </div>
                </div>
                </div>            
             </div>
          </div>

          <div class="slider-item s5">
             <div class="slider-card">
                <img src="https://images.unsplash.com/photo-1512820790803-83ca734da794?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1498&q=80" class="course_image">
                <div class="slider-item-info">
                <div class="course-title">Tsimilogo King</div>
                <div class="course-title2">peer</div>
                <div class="slider-item-description">
                   <div>
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
                   </div>
                </div>
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
     mounted() {

        setTimeout(function () {
            const slider1 = document.querySelector('.slider-wrapper');
        slider1.style.removeProperty('height')
        slider1.style.removeProperty('perspective')
        slider1.style.perspective = '1300px'
        slider1.style.height = '730px'

     
}, 100);
       
        document.addEventListener('DOMContentLoaded', () => {
  
  const __ms = document.querySelector('.micro-slider');
  
  const __msSlider = new MicroSlider(__ms, { indicators: true, indicatorText: '' });
  
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
    },

    methods: {
        changeClass() {
            const slider1 = document.querySelector('.slider-wrapper');
        // slider1.classList.add('slider-wrapper-resize')
        // setInterval(console.log(slider1), 1000);
        console.log(slider1)
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
    align-items: center;
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
    width: 500px !important;
    background-color: #04293a;
border-bottom-left-radius: 20px;
border-bottom-right-radius: 20px;

}

.slider-item-description {
    height: 20%;
    text-align: center;
    margin-top: 20px;
    margin-bottom: 20px;
    font-size: 20px;
    color: rgba(255, 255, 255, 0.686);
   

}

.course_image {
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
}
.course-title2 {
    font-size: 22px;
    letter-spacing: 1px;
    color: white;
    font-weight: 100;
    /*color: #4b4bff;*/
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

.micro-slider ul {
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
</style>