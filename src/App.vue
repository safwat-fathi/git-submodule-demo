<template>
  <h1>Git sub module POC (Prove Of Concept)</h1>
  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi voluptate laborum consequatur doloremque tenetur voluptatibus.</p>
</template>

<script>
import { sum } from "../utils/sum";

export default {
  name: "App",
  mounted() {
    const sumResult = sum(2, 3);
    console.log(sumResult);
  },
};
</script>

<style>
</style>
