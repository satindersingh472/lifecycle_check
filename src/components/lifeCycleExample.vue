<template>
  <div>
    <h1 class="heading">This is the heading</h1>
    <p class="below_heading">This is below heading</p>
  </div>
</template>

<script>
export default {
  beforeCreate: function () {
   let box = document.getElementsByClassName(`heading`); 
    box[`innerHTML`][`style`][`color`] = `red`;
  },
};
</script>

<style scoped>
div {
  text-align: center;
}
</style>