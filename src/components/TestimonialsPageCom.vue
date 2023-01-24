<template >
    <div id="heading">
        <h1>testimonials</h1>
        <h5>what people say about me and my work</h5>
    </div>
    <div id="testimonial">
        <div id="test">
            <div class="text">Mudassar Khopatkar is a highly competent and focused web developer. His friendly disposition draws his colleagues to him and he is impressionable to everyone he comes in contact with.</div>
            <div class="image"></div>
        </div>
        <div id="test">
            <div class="text">Mudassar khopatkar is a dedicated person , he strives to reach his goals and will put twice the amount of work in to achieve everything . He is a extremely talented person with many skills .</div>
            <div class="image"></div>
        </div>
        <div id="test">
            <div class="text">It is my great pleasure to have worked with Mudassar Khopatkar as he is a good team worker.He can collaborate and communicate with others on their ideas.</div>
            <div class="image"></div>
        </div>
        <div id="test">
            <div class="text">I am profoundly impressed with his intense focus and commitment. I am convinced that he can make a more valuable contribution for future endeavours.</div>
            <div class="image"></div>
        </div>
        <div id="test">
            <div class="text">Mudassar shows a lot of promise as a software developer. When he is focused, he works very diligently. His coding skills are gradually and steadily improving over time. I'm always happy seeing Mudassar grow as a developer, and I hope he continues to work hard.</div>
            <div class="image"></div>
        </div>
        <div id="test">
            <div class="text"></div>
            <div class="image"></div>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
#heading{
    width: 88%;
    height: 10%;
    display: flex;
    flex-direction: column;
    flex-wrap: nowrap;
    justify-content: start;
    align-items: flex-end;
}
#heading h1{
    color: white;
    text-align: left;
    letter-spacing: 2px;

}
#heading h5{
    color: #ecb365;
    text-align: left;
    letter-spacing: 1px;
}
#testimonial{
    height: 70%;
    width: 100%;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    gap: 20px;
}
#test{
    width: 44%;
    height: 32%;
    background-color: #04293a;
    border-radius: 12px;
    box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px, rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px, rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;
}
.text{
    height: 60%;
    width: 100%;
    color: rgba(255, 255, 255, 0.686);
    font-family: PRO;
    padding-left: 20px;
        padding-right: 20px;
    font-size: 20px;
    letter-spacing: 1px;
    display:flex;
    flex-direction: column;
    flex-wrap: nowrap;
    justify-content: center;
    align-items: center;
    text-align: left;
}
.image{
    height: 40%;
    width: 100%;
}
</style>