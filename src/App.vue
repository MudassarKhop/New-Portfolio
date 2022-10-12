<template>

  <router-view/>
</template>

<style>
*{
  margin: 0;
  padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: #18315b;
  color: #2c3e50;
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

/* nav a.router-link-exact-active {
  color: white;
  text-decoration: none;
} */
</style>
