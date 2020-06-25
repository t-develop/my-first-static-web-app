<template>
  <div>
    <div>Hello {{value}} </div>
    <div>azure static web apps</div>

    <section>
      <div class="A">
        class A division.
      </div>
      <div class="B">
        class B division.
      </div>

    </section>
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

<style scoped>
section{
  margin: 3em;
  border: 2px, black solid;
}

.A{
  background-color: lightblue;
}

.B{
  background-color: lightcoral;
}
</style>>
