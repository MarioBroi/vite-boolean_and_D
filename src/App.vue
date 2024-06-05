<script>
import { RouterView } from "vue-router";
import AppHeader from "./partials/AppHeader.vue";

export default {
  name: 'App',
  components: {
    AppHeader,
  }

}
</script>

<template>

  <AppHeader />
  <RouterView />

</template>

<style scoped></style>