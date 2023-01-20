<template >
    <div id="heading">
        <h1>testimonials</h1>
        <h5>what people say about me and my work</h5>
    </div>
    <div id="cards">
     <div id="test"></div>
     <div id="test"></div>
     <div id="test"></div> 
     <div id="test"></div> 
     <div id="test"></div> 
   </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
#heading{
    width: 83%;
    height: 10%;
    display: flex;
    flex-direction: column;
    flex-wrap: nowrap;
    justify-content: end;
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
#cards{
    height: 70%;
    width: 85%;
    /* border: 3px solid red;  */
    display: flex;
    flex-wrap: nowrap;
    justify-content: center;
    align-items: center;  
    gap: 25px; 
}
#test{
    display: flex;
    flex-direction: column;
    flex-wrap: nowrap;
    justify-content: center;
    align-items: center;
    height: 90%;
    width: 350px;
    background-color: #04293a;
    border-radius: 12px;
    transition: 0.4s ease-in;
    box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px, rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px, rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;
}
#test:hover{
width: 600px;
transition: 0.4s ease-in;

}
</style>