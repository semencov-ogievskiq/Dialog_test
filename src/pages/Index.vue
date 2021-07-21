<template>
  <div>
    <h1>Интерфейс аналитика</h1>
    <div class="container">
        <div class="col1">
            <Filters/>
            <ListMessages/>
        </div>
        <div class="col2">
            <WorkMessages/>
        </div>
    </div>
  </div>
</template>

<script>
import WorkMessages from '../components/WorkMessages.vue'
import Filters from '../components/Filters.vue'
import ListMessages from '../components/ListMessages.vue'
export default {
  name: 'HelloWorld',
  components: {
      WorkMessages,
      Filters,
      ListMessages
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
        margin: 0.5rem;
    }
    .col1 {
        flex: 1 0 100%;
        margin: 0.5rem;
        min-width: 10rem;
    }
    .col2 {
        flex: 1 0 100%;
        min-width: 10rem;
        margin: 0.5rem;
    }
    @media screen and (min-width: 1100px){
        .col1 {
            flex: 1 0 calc(40% - 1rem);
        }
        .col2 {
            flex: 1 0 calc(60% - 1rem);
        }
    }
</style>
