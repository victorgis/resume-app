<template>
  <div class="header-nav">
    <nav :style="{ width: '100%' }">
      <h1 class="header-h1">Resume App</h1>
    </nav>
  </div>
</template>

<script>
export default {
  name: "ResumeAppHeader",

  data() {
    return {};
  },

  mounted() {},

  methods: {},
};
</script>

<style scoped>
.header-nav {
  background: #3564;
  padding: 8px;
}
.header-h1 {
  margin: 0;
}
</style>