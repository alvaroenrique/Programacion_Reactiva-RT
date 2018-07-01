<template>
  <div id="app">
    <h2>Ejemplo práctico 1</h2>
    <hr>

    <h4>var1 = {{var1}}</h4> 
    <h4>var2 = {{var2}}</h4> 
    <h4>var3 (A x B) = {{var1 * var2}}</h4>

    <div>
      Cambiar el valor de Var1: <input type="text" v-model="var1">
    </div>
    <div>
      Cambiar el valor de Var2: <input type="text" v-model="var2">
    </div>
  </div>
</template>

<script>
import { Observable } from "rxjs/Observable";
import "rxjs/add/observable/of";

export default {
  name: "Ejemplo1",
  data() {
    return {
      var1: 3,
      var2: 10
    };
  },
  methods: {},
  created() {}
};
</script>

<style>
input {
  text-align: center;
  width: 50px;
}
</style>
