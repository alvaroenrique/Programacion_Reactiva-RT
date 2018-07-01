<template>
  <div id="app">
    <Ejemplo1 class="var"></Ejemplo1>
  </div>
</template>

<script>
import Ejemplo1 from "./components/Ejemplo1";
import "bootstrap/dist/css/bootstrap.css";

export default {
  name: "App",
  components: { Ejemplo1 }
};
</script>

<style>
.var {
}
#app {
  text-align: center;
}
</style>
