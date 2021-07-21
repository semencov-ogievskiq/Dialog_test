<template>
  <div class="block">
    <div>Фильтры</div>
    <div class="block-checkbox">
      <input type="checkbox" >
    </div>
    <div class="block-checkbox">
      <input type="checkbox" >
    </div>
    <div class="block-checkbox">
      <input type="checkbox" >
    </div>
    <div class="block-checkbox">
      <input type="checkbox" >
    </div>
    <div class="block-checkbox">
      <input type="checkbox" >
    </div>

    <div class="block-checkbox">
      <input type="checkbox" >
    </div>
    <div class="block-checkbox">
      <input type="checkbox" >
    </div>
  </div>
</template>

<script>
export default {
  name: 'Filters'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .block > div {
    font-size: 20px;
    color: #3E4956;
  }
  .block-checkbox {
    width: 50%;
    display: inline-block;
  }
</style>
