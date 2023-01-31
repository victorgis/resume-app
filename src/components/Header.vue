<template>
  <div class="header-nav">
    <nav>
      <h1>Resume App</h1>
      <div class="socials">
        <ul>
          <li>
            <a href="https://veespatial.space"
              ><i class="fa-solid fa-globe color-fa"></i
            ></a>
          </li>
          <li>
            <a href="https://twitter.com/victorgis"
              ><i class="fa-brands fa-twitter color-fa"></i
            ></a>
          </li>
          <li>
            <a href="thhps://linkedin.com/in/victoressang"
              ><i class="fa-brands fa-linkedin color-fa"></i
            ></a>
          </li>
        </ul>
      </div>
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
nav {
  display: flex;
  justify-content: space-between; /* or center, flex-start, flex-end */
  align-items: center; /* or flex-start, flex-end, baseline */
  padding: 0 20px;
}

.socials ul {
  display: inline-flex;
}
.socials li {
  list-style-type: none;
  padding: 0 20px;
}

.color-fa {
  color: black;
}
</style>