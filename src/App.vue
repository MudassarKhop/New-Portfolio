<template>

  <router-view/>
</template>

<style>
@font-face {
  font-family: Pro;
  src: url(./assets/FeelingSoon-1GVr0.otf);
}

@font-face {
  font-family: Pro2;
  src: url(./assets/MardeSauvePersonalUse-ywaPd.ttf);
}
@font-face {
  font-family: Pro7;
  src: url(./assets/DechorRothen-3zGj8.otf);
}
@font-face {
  font-family: Pro3;
  src: url(./assets/MusticaproSemibold-2OG5o.otf);
}

@font-face {
  font-family: Pro4;
  src: url(./assets/PentaySansRegItalic-48n4.ttf);
}

*{
  margin: 0;
  padding: 0;
}
h3{
  font-family: Pro;
}
h2{
  font-family: Pro;
}
h1{
  font-family: Pro;
}
h4{
  font-family: Pro;
}
h5{
  font-family: Pro;
}
p{
  font-family: Pro3;
}
span{
  font-family: Pro;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: #041424;
  
  color: #2c3e50;
}
body::-webkit-scrollbar{
  display: none;
}
#logo{
  width: 30%;
  /* border: 3px solid white; */
  display: flex;
  flex-direction: row;
  flex-wrap: nowrap;
  color: #fd3e57;
  transition: ease 1s;

}
#logo:hover{
color: #ec6274;
transition: ease 1s;
}
nav {
  padding: 40px;
  display: flex;
  flex-direction: row;
  flex-wrap: nowrap;
  justify-content: center;
  align-content: flex-end;
  color: white;
  /* border: 3px solid #fd3e57; */
}
/* #logo{
  margin-right: 100px;
} */

nav a {
  font-size: 30px;
  font-weight: bold;
  color: #2c3e50;
  margin-right: 40px;
  color: white;
  text-decoration: none;
  transition: ease 1s;

}
nav a:hover{
color: #fd3e57;
transition: ease 1s;
}
#buttons{
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: start;
  align-content: flex-start;
  width: 100%;
  gap: 30px;
  margin-top: 30px;
  padding-bottom: 35px;
 }
 button{
  width: 30%;
  height: 70px;
  border-radius: 12px;
  font-size: 25px;
  letter-spacing: 2px;
  border: none;
  color: rgb(223, 223, 223);
  font-family: Pro;
  text-align: center;
    box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px, rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px, rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;
  text-shadow: 0 4px 4px black;
  transition: 0.2s ease-in;

 }  
 button:hover{
  transition: 0.2s ease-in;
  color: rgba(255, 255, 255, 0.87);

 }
 #b1{
  background-color: #c69653;
 }
 #b1:hover{
  background-color: #c69653ae;
  box-shadow: none;
 }
 #b2{
background-color: #0b3447;
 }
 #b2:hover{
  background-color: #0b34478e;
        box-shadow: none;
 }
/* nav a.router-link-exact-active {
  color: white;
  text-decoration: none;
} */
</style>
