<template>
  <div id="app">
    <router-view />
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      input: ""
    };
  },
  created() {
    console.log("this====", this);
  }
};
</script>

<style></style>
