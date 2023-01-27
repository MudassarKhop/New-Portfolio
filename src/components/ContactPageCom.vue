<template>
 <div id="contactbox">
  <div id="bimg">
    <!-- <img src="https://i.postimg.cc/mZtX4KRV/d-funny-character-cartoon-sympathetic-looking-business-man-dear-person-suit-glasses-tie-47992412-tra.png" alt=""> -->
  </div>
  <div id="form">
    <div id="heading">
        <h1>contact me</h1>
        <h5>send me an email or review of my portfolio</h5>
    </div>
    <form action="https://formspree.io/f/mrgdynyj" method="POST">
      <label id="name">
    <input type="name" name="name" placeholder="Name">
    <input type="name" name="name" placeholder="Surname">

  </label>
  <label id="email">
    <input id="e1" type="email" name="email" placeholder="Email">
    <input id="n1" type="tel" name="number" placeholder="Number">
  </label>
  <label id="message">
    <textarea name="message" placeholder="Message"></textarea>
  </label>
  <!-- your other form fields go here -->
  <div id="buttonss">
    <button id="b1" type="reset">Reset</button>
    <button id="b2" type="submit">Send</button>
  </div>
</form>
  </div>
 </div>
</template>
<script>
export default {
    
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
    align-items: flex-start;
}

#heading h1 {
    color: white;
    text-align: right;
    letter-spacing: 2px;

}
label{
  display: flex;
  flex-direction: column;
  text-align: start;
  color: white  ;
}
textarea{
  height: 200px;
  width: 820px;
  border-radius: 12px;
  background-color: #041424;
  border: none;
  padding-left: 20px;
  padding-top: 20px;
  color: white;
  font-size: 25px;
  font-family: Pro;
  letter-spacing: 2px;
  overflow-y: scroll;
}
textarea:placeholder-shown{
  font-size: 22px;
  font-family: Pro;
}
::-webkit-scrollbar {
  display: none;
}
#name{
  display: flex;
  flex-direction: row;
  gap: 15px;
}
#email{
  display: flex;
  flex-direction: row;
  gap: 15px;
}
#e1{
  width: 550px;
} 
#n1{
  width: 250px;
}
input{
  height: 80px;
  width: 400px;
  border-radius: 12px;
  background-color: #041424;
  border: none;
  font-size: 25px;
  font-family: Pro;
  padding-left: 20px;
  color: white;
  letter-spacing: 2px;
}
input:placeholder-shown {
  font-size: 22px;
  font-family: Pro;
}
#heading h5 {
    color: #ecb365;
    text-align: right;
    letter-spacing: 2px;
}
#contactbox{
  overflow: hidden;
  width: 90%;
  height: 80%;
  background-color: #04293a;
  box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px, rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px, rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;
  border-radius: 20px;
  display: flex;
  flex-wrap: nowrap;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}
#bimg{
  width: 50%;
  height: 100%;
  display: flex;
  flex-wrap: nowrap;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}
#form{
  width: 50%;
  height: 100%;
  display: flex;
  flex-wrap: nowrap;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
}
#buttonss{
  width: 100%;
  display: flex;
  flex-direction: row;
  justify-content: start;
  align-items: flex-start;
  gap: 20px;
}
form{
  margin-top: 22px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  gap: 25px;
}
button{
  color: rgba(255, 255, 255, 0.686);
  box-shadow: none;
}
</style>