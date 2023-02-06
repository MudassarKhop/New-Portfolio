<template>

  <AllProjectsCom />
  <section id="footer">
    <div>
      <h5>©2022-present | all-rights-reserved</h5>
    </div>
  </section>
</template>
<script>
import AllProjectsCom from '../components/AllProjectsCom.vue';
export default {
  components: { AllProjectsCom },
}
</script>
<style scoped>
#projects {
  width: 100%;
  padding: 50px;
min-height: 150vh;
  background-color: #041424;
}

#footer {
  height: 5vh;
  background-color: #04293a;
}

#footer h5 {
  font-size: 16px;
  text-align: center;
  color: rgba(223, 223, 223, 0.695);
}

#footer div {
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