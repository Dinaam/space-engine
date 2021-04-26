<template>
  <div class="back-nav">
      <ul>
        <li>
          <font-awesome-icon class="pulse red" icon="home" />
        </li>
      </ul>
  </div>
</template>

<script>
import { library } from '@fortawesome/fontawesome-svg-core';
import { FontAwesomeIcon } from "@fortawesome/vue-fontawesome";
import { faHome } from "@fortawesome/free-solid-svg-icons";

library.add(faHome);
export default {
  components:{
    FontAwesomeIcon
  }

};
</script>

<style scoped>
ul li{
  list-style: none;
  text-align: center;
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
