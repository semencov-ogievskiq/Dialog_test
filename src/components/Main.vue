<template>
  <main>
    <div>
        <slot/>
    </div>
  </main>
</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    main {
        position: absolute;
        width: 100%;
        z-index: 1;
    }
    main > div {
        padding: 1rem 1.5rem 1rem 5rem;
    }
</style>
