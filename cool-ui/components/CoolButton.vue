<template>
  <div>
    <button @click="clickHandler">Click me bro I'm a cool button</button>
  </div>
</template>

<script setup lan="ts">
const clickHandler = () => {
  alert("You clicked me!");
};
</script>
