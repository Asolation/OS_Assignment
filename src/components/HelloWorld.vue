<template>
  <div class="container-fluid p-5 text-black">
    <h1>My First Bootstrap Page</h1>
    <p>Enter number of process: </p>
    <input v-model.number ="process" type="number">
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

