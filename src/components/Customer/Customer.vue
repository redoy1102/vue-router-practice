<template>
<div>
  <h2>The customer page</h2>
  <hr>
  <button class="btn btn-success" @click="navigateToHome" >Go to home</button>
</div>
</template>

<script>
export default {
methods: {
  navigateToHome(){
    this.$router.push('/')
  }
}
}
</script>

<style scoped>

</style>