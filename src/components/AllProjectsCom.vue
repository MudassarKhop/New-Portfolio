<template>
    <section id="projects">
        <div id="words">
    <div id="heading">
            <h1>all projects</h1>
            <h5>everyone I worked on in the academy</h5>
        </div>
        <div id="heading1">
  <button id="b2" @click="homePage()">Home</button>
        </div>
</div>
<div id="card" type="button" data-bs-toggle="modal" data-bs-target="#exampleModal">
                <div id="img">
                    <img src="https://i.postimg.cc/L5txVCqv/Screenshot-17.png" alt="">
                </div>
                <div id="name">
                  <h1>CapStone Project</h1>
                  <p>Full Stack project built with <span>VUE.js</span> and <span>NODE.js</span> backend.</p>
                </div>
            </div>
<!-- Modal -->
<div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h1 class="modal-title fs-5" id="exampleModalLabel">Modal title</h1>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        ...
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div>
  </div>
</div>
<!-- modal -->
<div id="card" type="button" data-bs-toggle="modal" data-bs-target="#exampleModal2">
                <div id="img">
                    <img src="https://i.postimg.cc/prVJv2cb/Screenshot-18.png" alt="">
                </div>
                <div id="name">
                  <h1>Node Final Project</h1>
                  <p>Ecommerce end of module project built in <span>NODE.js</span> to test backend skills.</p>
                </div>
            </div>
            <!-- Modal -->
<div class="modal fade" id="exampleModal2" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h1 class="modal-title fs-5" id="exampleModalLabel">Modal titlee</h1>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        ...
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div>
  </div>
</div>
<!-- modal -->
<div id="card" type="button" data-bs-toggle="modal" data-bs-target="#exampleModal3">
                <div id="img">
                    <img src="https://i.postimg.cc/3xvdfsrK/Screenshot-19.png" alt="">
                </div>
                <div id="name">
                  <h1>Car Website</h1>
                  <p>Car website built with <span>BootStrap</span> and filters made with <span>JavaScript</span>.</p>
                </div>
            </div>
                     <!-- Modal -->
<div class="modal fade" id="exampleModal3" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h1 class="modal-title fs-5" id="exampleModalLabel">Modal titlee3</h1>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        ...
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div>
  </div>
</div>
<!-- modal -->
            <div id="card">
                <div id="img">
                    <img loading="lazy" src="https://i.postimg.cc/c4HQbnJQ/Screenshot-21.png" alt="">
                </div>
                <div id="name">
                  <h1>Group Ecom Project</h1>
                  <p>Full Stack project built with <span>VUE.js</span> and <span>NODE.js</span> backend.</p>
                </div>
            </div>
            <div id="card">
                <div id="img">
                    <img loading="lazy" src="https://i.postimg.cc/hGFTvZ1r/Screenshot-22.png" alt="">
                </div>
                <div id="name">
                  <h1>Restuarantly Mockup</h1>
                  <p>Task was to replicate the mockup website using <span>BootStrap</span>.</p>
                </div>
            </div>
            <div id="card">
                <div id="img">
                    <img loading="lazy" src="https://i.postimg.cc/hP59WtJN/Screenshot-23.png" alt="">
                </div>
                <div id="name">
                  <h1>Vue Portfolio</h1>
                  <p>Final portfolio in the coding academy using <span>Vue.js</span> aswell as <span>JavaScript</span>.</p>
                </div>
            </div>
    </section>
</template>
<script>
import router from '@/router';

export default {
    methods: {
        homePage() {
            window.location = '/'
        }
    }
}
</script>
<style scoped>
span{
    color: white;
    text-decoration: none;
    text-shadow: none;
}
#projects{
    width: 100%;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    height: 100%;
    gap: 50px;
    padding-top: 20px;
    /* border: 3px solid red; */
}
#card{
    display: flex;
    flex-direction: column;
    flex-wrap: nowrap;
    justify-content: center;
    align-items: center;
    height: 650px;
    width: 27%;
    border-radius: 12px;
    transition: 0.3s ease-in;
    background-color: #04293a;
    box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px, rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px, rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;
}
#card:hover{
    transition: 0.3s ease-in;
    box-shadow: rgba(159, 143, 79, 0.56) 0px 22px 70px 4px;}
#img{
    height: 70%;
    width: 100%;
}
img{
    height: 100%;
    width: 100%;
    aspect-ratio: 1;
    object-fit:cover;
    border-top-right-radius: 12px;
    border-top-left-radius: 12px;
}
#name{
    height: 30%;
    width: 90%;
    /* border: 1px solid red; */
    display: flex;
    flex-direction: column;
    flex-wrap: nowrap;
    justify-content: center;
    align-items: flex-start;
    color: #ecb365;
    letter-spacing: 1px;
    margin-bottom: none !important;
}
#home h1{
    margin-bottom: none;
}
#name p{
    color: rgba(255, 255, 255, 0.686);
    letter-spacing: 1px;
    font-size: 22px;
    text-align: start;
    margin-bottom: none !important;
}
a{
    text-decoration:none;
    color: white;
}
span{
    color: white;
    text-shadow: none;
    letter-spacing: 1px;
}

#words{
    width: 97%;
    height: 13%;
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    justify-content: center;
    align-items: center;  
}
#heading{
    width: 44%;
    display: flex;
    flex-direction: column;
    flex-wrap: nowrap;
    justify-content: start;
    align-items: flex-start;

}
#heading1{
    width: 44%;
    display: flex;
    flex-direction: row ;
    flex-wrap: nowrap;
    justify-content: end;
    align-items: flex-end;
    gap: 20px;

}
#heading h1{
    color: white;
    text-align: left;
    letter-spacing: 2px;
    justify-content: start;
    align-items: flex-start;

}
#heading h5{
    color: #ecb365;
    text-align: left;
    letter-spacing: 1px;
    justify-content: start;
    align-items: flex-start;
}
.modal{
    background-color: #04293a;
}
@media only screen and (max-width: 600px) and (min-width: 389px) {
  #words[data-v-06c8f176] {
    width: 100%;
    height: 13%;
    display: flex;
    flex-direction: column;
    flex-wrap: nowrap;
    justify-content: center;
    align-items: center;
}
#heading{
  width: 100%;
  justify-content: center !important;
  align-items: center !important;
}
#heading h1{
  font-size: 25px;
}
#heading1{
  width: 100%;
  justify-content: center !important;
  align-items: center !important;
}
#heading h5{
  font-size: 17px;
  justify-content: center !important;
  align-items: center !important;
  text-align: center;
}
#card{
  width: 85%;
}

#card h1{
  font-size: 22px;
margin-top: 10px;
}
#card p{
  font-size: 17px;
}

}
</style>