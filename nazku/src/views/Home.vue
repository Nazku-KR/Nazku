<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" :style="{ width: '200px', height: '200px' }" />
    <HelloWorld msg="Welcome to Nazku" />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src

@Component({
  components: {
    HelloWorld,
  },
})
export default class Home extends Vue {}
</script>
