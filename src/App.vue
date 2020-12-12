<template>
  <ion-app>
    <ion-router-outlet />
    <HelloWorld msg="Hello Vue 3.0 + Vite + Ionic" />
  </ion-app>
</template>

<script lang="ts">
import { IonApp, IonRouterOutlet } from "@ionic/vue";
import { defineComponent } from "vue";
import HelloWorld from "./components/HelloWorld.vue";

export default defineComponent({
  name: "App",
  components: {
    HelloWorld,
    IonApp,
    IonRouterOutlet,
  },
});
</script>
