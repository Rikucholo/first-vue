<template>
  <p>{{items[0].name}}</p>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

export default class HelloWorld extends Vue {
  items:{name: string, price: number, quantity: number}[] = [
    {
      name: "鉛筆",
      price: 300,
      quantity: 0
    },
    {
      name: "ノート",
      price: 300,
      quantity: 0
    },
    {
      name: "消しゴム",
      price: 300,
      quantity: 0
    }
  ];

  msg = "Hello world";
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
