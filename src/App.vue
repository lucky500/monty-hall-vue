<template>
  <div class="monty-hall">
    <!-- <Gift /> -->
  </div>
  <div class="doors">
    <Door number="1" hasGift="true" />
    <Door number="2" hasGift="false" />
    <Door number="3" hasGift="false" />
  </div>
</template>

<script>
// import Gift from "./components/Gift";
import Door from "./components/Door";

export default {
  name: 'App',
  components: {
    // Gift,
    Door
  }
}
</script>

<style>
:root {
  --frame-border: 5px solid #c77c1a;
}

body {
  background: linear-gradient(to right, rgb(21, 153, 87), rgb(21, 87, 153));
}

.doors {
  display: flex;
  justify-content: space-around;
}
</style>
