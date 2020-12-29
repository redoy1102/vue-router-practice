<template>
  <ul class="nav nav-pills bg-primary">
    <li class="nav-item">
      <router-link class="nav-link text-white" to="/" >Home</router-link>
    </li>
    <li class="nav-item">
      <router-link class="nav-link text-white" to="/customer" >Customer</router-link>
    </li>
    <li class="nav-item">
      <router-link class="nav-link text-white" to="/customerDetail" >CustomerDetail</router-link>
    </li>
    <li class="nav-item">
      <router-link class="nav-link text-white" to="/customerEdit"  >CustomerEdit</router-link>
    </li>
    <li class="nav-item">
      <router-link class="nav-link text-white" to="/customerStart"  >CustomerStart</router-link>
    </li>
  </ul>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>

</style>