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

<div class="day">
  <span>8:00</span><div class="hour"></div>
  <span>9:00</span><div class="hour"></div>
  <span>10:00</span><div class="hour"></div>
  <span>11:00</span><div class="hour"></div>
  <span>12:00</span><div class="hour"></div>
  <span>13:00</span><div class="hour"></div>
  <span>14:00</span><div class="hour"></div>
  <span>15:00</span><div class="hour"></div>
  <span>16:00</span><div class="hour"></div>
  <span>17:00</span><div class="hour"></div>
  <span>18:00</span><div class="hour"></div>
</div>
<div class="day">
  <span>8:00</span><div class="hour"></div>
  <span>9:00</span><div class="hour"></div>
  <span>10:00</span><div class="hour"></div>
  <span>11:00</span><div class="hour"></div>
  <span>12:00</span><div class="hour"></div>
  <span>13:00</span><div class="hour"></div>
  <span>14:00</span><div class="hour"></div>
  <span>15:00</span><div class="hour"></div>
  <span>16:00</span><div class="hour"></div>
  <span>17:00</span><div class="hour"></div>
  <span>18:00</span><div class="hour"></div>
</div>
<div class="day">
  <span>8:00</span><div class="hour"></div>
  <span>9:00</span><div class="hour"></div>
  <span>10:00</span><div class="hour"></div>
  <span>11:00</span><div class="hour"></div>
  <span>12:00</span><div class="hour"></div>
  <span>13:00</span><div class="hour"></div>
  <span>14:00</span><div class="hour"></div>
  <span>15:00</span><div class="hour"></div>
  <span>16:00</span><div class="hour"></div>
  <span>17:00</span><div class="hour"></div>
  <span>18:00</span><div class="hour"></div>
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

.day{
  display: inline;
}

.hour{
  margin: 0;
  border: 1px solid black;
}

span{
  vertical-align: top;
}
</style>
