<script>
import { RouterView } from "vue-router";

import AppHeader from "./partials/AppHeader.vue";
import AppFooter from "./partials/AppFooter.vue";
export default {
  name: 'App',
  components: {
    AppHeader,
    AppFooter,
  }

}
</script>

<template>

  <AppHeader />
  <RouterView />
  <AppFooter />

</template>
