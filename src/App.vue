<template>
  <div>
    <span>Hello {{value}} </span>
    <span>azure static web apps</span>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      value: "World"
    };
  }
};
</script>
