<template>
  <div class="top">
    <navbar></navbar>
    <h1 class="title">
      Space Engine
    </h1>
    <latest></latest>
  </div>
</template>

<script>
import Navbar from "./Navbar.vue";
import Latest from "./Latest.vue";

export default {
  name: "Home",
  components: {
    Navbar,
    Latest
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.top{
    margin-top: 44px;
}
.title {
  font-size: 36px;
  vertical-align: Top;
  margin-left: 22%;
}

</style>
