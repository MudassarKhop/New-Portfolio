<template>
 <div id="contactbox">
  <div id="bimg">
    <img src="https://i.postimg.cc/mZtX4KRV/d-funny-character-cartoon-sympathetic-looking-business-man-dear-person-suit-glasses-tie-47992412-tra.png" alt="">
  </div>
  <div id="form">
    <form
  action="https://formspree.io/f/mrgdynyj"
  method="POST"
>
  <label>
    Your email:
    <input type="email" name="email">
  </label>
  <label>
    Your message:
    <textarea name="message"></textarea>
  </label>
  <!-- your other form fields go here -->
  <button type="submit">Send</button>
</form>
  </div>
 </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
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
</style>