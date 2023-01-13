<template>
    <div id="heading">
        <h1>projects</h1>
        <h5>some of my work and projects</h5>
    </div>
    <div id="projects">

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
#projects{
    height: 75%;
    width: 100%;
    border: 3px solid red;
}
</style>