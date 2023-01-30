<template>
<div id="words">
    <div id="heading">
            <h1>featured projects</h1>
            <h5>some of my work and projects</h5>
        </div>
        <div id="heading1">
            <button id="b1"><a href="https://www.github.com/mudassarkhop/" target="_blank">GITHUB</a></button>
  <button id="b2"><router-link @click.native="scrollToTop" to="/projects">All Projects</router-link></button>
        </div>
</div>
    <div id="projects">
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
        <h1 class="modal-title fs-5" id="exampleModalLabel">CapStone Project</h1>
        <button style="background-color:transparent" type="button" id="close-button" data-bs-dismiss="modal" ><i class="fa-solid fa-xmark"></i></button>
      </div>
      <div class="modal-body">
        <p>Full Stack project built with <span>VUE.js</span> and <span>NODE.js</span> backend. This project was the final project of the academy, it tested our backend and frontend skills in one go.</p>
      </div>
      <div class="modal-footer">
        <button id="b3"><a href="https://www.github.com/mudassarkhop/" target="_blank">GITHUB</a></button>
        <button id="b4"><a href="#">Live Link</a></button>
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
        <h1 class="modal-title fs-5" id="exampleModalLabel">Node Final Project</h1>
        <button style="background-color:transparent" type="button" id="close-button" data-bs-dismiss="modal" ><i class="fa-solid fa-xmark"></i></button>
      </div>
      <div class="modal-body">
        <p>Ecommerce end of module project built in <span>NODE.js</span> to test backend skills. On this particular project we worked in pairs. This was our first node project and it was a tough one because our backend kept crashing, but I was proud of my frontend on this website</p></div>
      <div class="modal-footer">
        <button id="b3"><a href="https://www.github.com/mudassarkhop/" target="_blank">GITHUB</a></button>
        <button id="b4"><a href="#">Live Link</a></button>
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
        <h1 class="modal-title fs-5" id="exampleModalLabel">Car Website</h1>
        <button style="background-color:transparent" type="button" id="close-button" data-bs-dismiss="modal" ><i class="fa-solid fa-xmark"></i></button>
      </div>
      <div class="modal-body">
        <p>Car website built with <span>BootStrap</span> and filters made with <span>JavaScript</span>. This was an interesting project because this was the first project where we used an array. We learn't how to sort and filter our products and this.</p>
      </div>
      <div class="modal-footer">
        <button id="b3"><a href="https://www.github.com/mudassarkhop/" target="_blank">GITHUB</a></button>
        <button id="b4"><a href="#">Live Link</a></button>
      </div>
    </div>
  </div>
</div>
<!-- modal -->
    </div>
</template>
<script>
export default {
    methods: { 
  scrollToTop() {
    window.scrollTo(0,0);
  }
}
}
</script>
<style scoped>
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
    width: 100%;
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
#projects{
    height: 65%;
    width: 100%;
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    justify-content: center;
    align-items: center;

    /* border: 3px solid red; */
}
#card{
    display: flex;
    flex-direction: column;
    flex-wrap: nowrap;
    justify-content: center;
    align-items: center;
    height: 95%;
    width: 27%;
    border-radius: 12px;
    transition: 0.3s ease-in;
    background-color: #04293a;
    border: none !important;
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

.modal-content{
    background-color: #04293a;
    border: none;
    width: 700px;
    height: 500px;
    font-size: 25px;
    color: rgba(255, 255, 255, 0.686);
    letter-spacing: 2px;
}
.modal-content h1{
    color: #ecb365;
    letter-spacing: 2px;
    font-size: 30px !important;
    padding-left: 20px;
}
.fa-xmark{
    color: white;
    font-size: 50px;
    transition:0.2s ease;
}
.fa-xmark:hover{
    color: #ecb465bb;
    font-size: 50px;
    transition:0.2s ease;
}
#close-button{
    box-shadow: none;
    width: 60px;
}
#b3{
    background-color: #c69653;
}
#b4{
    background-color: #0b3447;
    }
    .modal-footer{
        gap: 10px;
    }
    .modal-body {
    display: flex;
    flex-direction: column;
    flex-wrap: nowrap;
    justify-content: center;
}
</style>
