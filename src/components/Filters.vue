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
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .block {
    background: #FFFFFF;
    border: 1px solid #EFF0F2;
    box-sizing: border-box;
    border-radius: 4px;
    height: auto;
    padding: 1rem 1.5rem;
  }
  .block > div {
    font-size: 20px;
    color: #3E4956;
  }
  .block-checkbox {
    width: 50%;
    display: inline-block;
  }
</style>
