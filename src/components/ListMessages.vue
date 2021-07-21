<template>
  <div class="block">
    <div>Список сообщений</div>
    <hr>
    <Messages/>
    <Messages/>
  </div>
</template>

<script>
import Messages from './Messages'

export default {
  name: 'ListMessages',
  components: {
      Messages
  }
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
