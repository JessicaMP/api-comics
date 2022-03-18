<template>
  <div id="home">
    <h1>👋Hello world🌎</h1>
    <p>{{ count }}</p>
  </div>
</template>

<script>
import { mapState } from "vuex";

export default {
  name: "home-page",
  computed: {
    ...mapState(["count"]),
  },
};
</script>
