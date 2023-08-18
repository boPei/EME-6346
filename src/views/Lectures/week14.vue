<template>
    <div class="week1">
        <h1>Sorry,We are working on it</h1>
    </div>
  </template>

<script>
import pdf from 'vue-pdf'
export default {
  data() {
    return {
      tabPosition: 'left',
    };
  },
  components: {
    pdf
  }
  
};
</script>

<style scoped>
h1{
    font-size: 50px;
    margin-left: 30%;
    margin-top: 15%;
}
</style>