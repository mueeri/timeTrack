<template>
  <NavBar />
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import NavBar from "components/navigation/NavBar.vue";


export default defineComponent({
  name: 'MainLayout',

  components: {
    NavBar,
  },

  setup () {

  }
});
</script>
