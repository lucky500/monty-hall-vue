<template>
  <div class="monty-hall">
    <Gift />
  </div>
</template>

<script>
import Gift from "./components/Gift";

export default {
  name: 'App',
  components: {
    Gift
  }
}
</script>

<style>
body {
  background: linear-gradient(to right, rgb(21, 153, 87), rgb(21, 87, 153));
}
</style>
