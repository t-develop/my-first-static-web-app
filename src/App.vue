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
  <ul>
  <li><span>08:00</span><div class="hour"></div></li>
  <li><span>09:00</span><div class="hour"></div></li>
  <li><span>10:00</span><div class="hour"></div></li>
  <li><span>11:00</span><div class="hour"></div></li>
  <li><span>12:00</span><div class="hour"></div></li>
  <li><span>13:00</span><div class="hour"></div></li>
  <li><span>14:00</span><div class="hour"></div></li>
  <li><span>15:00</span><div class="hour"></div></li>
  <li><span>16:00</span><div class="hour"></div></li>
  <li><span>17:00</span><div class="hour"></div></li>
  <li><span>18:00</span><div class="hour"></div></li>
  </ul>
</div>
<div class="day">
  <ul>
  <li><span>08:00</span><div class="hour"></div></li>
  <li><span>09:00</span><div class="hour"></div></li>
  <li><span>10:00</span><div class="hour　registered">検索エンジンMTG</div></li>
  <li><span>11:00</span><div class="hour"></div></li>
  <li><span>12:00</span><div class="hour"></div></li>
  <li><span>13:00</span><div class="hour registered"></div></li>
  <li><span>14:00</span><div class="hour"></div></li>
  <li><span>15:00</span><div class="hour registered"></div></li>
  <li><span>16:00</span><div class="hour"></div></li>
  <li><span>17:00</span><div class="hour"></div></li>
  <li><span>18:00</span><div class="hour"></div></li>
  </ul>
</div>
<div class="day">
  <ul>
  <li><span>08:00</span><div class="hour"></div></li>
  <li><span>09:00</span><div class="hour"></div></li>
  <li><span>10:00</span><div class="hour"></div></li>
  <li><span>11:00</span><div class="hour"></div></li>
  <li><span>12:00</span><div class="hour"></div></li>
  <li><span>13:00</span><div class="hour"></div></li>
  <li><span>14:00</span><div class="hour"></div></li>
  <li><span>15:00</span><div class="hour"></div></li>
  <li><span>16:00</span><div class="hour"></div></li>
  <li><span>17:00</span><div class="hour"></div></li>
  <li><span>18:00</span><div class="hour"></div></li>
  </ul>
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
  display: inline-block;
}

.hour{
  margin: 0;
  border: 1px solid black;
  width: 200px;
  height: 50px;
  display: inline-block;
}

span{
  vertical-align: top;
}

li{
  list-style: none;
  /*display: inline-flex;*/
}

.registered{
background-color: lightcoral;
}

</style>
