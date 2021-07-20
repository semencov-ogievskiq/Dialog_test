<template>
  <div>
    <h1>Интерфейс аналитика</h1>
    <div class="col-left">
        <Filters/>
    </div>
    <div class="col-right">
        <WorkMessages/>
    </div>
  </div>
</template>

<script>
import WorkMessages from '../components/WorkMessages.vue'
import Filters from '../components/Filters.vue'
export default {
  name: 'HelloWorld',
  components: {
      WorkMessages,
      Filters
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    h1 {
        font-weight: 300;
        font-size: 23px;
        line-height: 27px;
        color: #3E4956;
    }
    .col-left, .col-right {
        position: absolute;
    }
    .col-left {
        width: 34.5%;
        padding-right: 0rem;
    }
    .col-right {
        width: 56.58%;
        padding: 0 1.5rem;
        left: 40%;
    }
</style>
