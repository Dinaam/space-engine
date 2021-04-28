<template>
  <div class="back-nav">
    <ul>
      <li>
        <font-awesome-icon size="2x" icon="home" /><br />
        Home
      </li>
      <li>
        <font-awesome-icon size="2x" icon="rocket" /><br />
        Launches
      </li>
      <li>
        <font-awesome-icon size="2x" icon="space-shuttle" /><br />
        Starlink
      </li>
      <li>
        <font-awesome-icon size="2x" icon="car" /><br />
        Roadster
      </li>
      <li>
        <font-awesome-icon size="2x" icon="book" /><br />
        History
      </li>
    </ul>
  </div>
</template>

<script>
import { library } from "@fortawesome/fontawesome-svg-core";
import { FontAwesomeIcon } from "@fortawesome/vue-fontawesome";
import { faHome,faRocket,faSpaceShuttle,faCar,faBook } from "@fortawesome/free-solid-svg-icons";

library.add(faHome,faRocket,faSpaceShuttle,faCar,faBook);

export default {
  components: {
    FontAwesomeIcon,
  },
};
</script>

<style scoped>
ul {
  padding: 0;
}
ul li {
  list-style: none;
  text-align: center;
  margin-bottom: 25%;
}

.back-nav {
  position: absolute;
  width: 10%;
  float: left;
  left: 10%;
  background-color: rgba(53, 59, 72, 0.8);
  border-radius: 25px;
}
</style>
