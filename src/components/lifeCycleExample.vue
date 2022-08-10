<template>
  <div>
    <h1 id="heading">This is the heading</h1>
    <p class="below_heading">This is below heading</p>
  </div>
</template>

<script>
export default {
  beforeCreate: function () {
 console.log(`I m mounted`);
  },
  created: function(){
console.log(`i m creatd`);
  },
  beforeMount: function(){
    console.log(`i m beforemount`);
  },
  mounted: function(){
    console.log(`i am in mounted`);
  }
};
</script>

<style scoped>
div {
  text-align: center;
}
</style>