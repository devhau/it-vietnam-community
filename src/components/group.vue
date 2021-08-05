<template>
  <div class="group">
    <Item v-for="item in Groups" :key="item" :data="item"/>
  </div>
</template>

<script>
import Item from "./item.vue";
import Data from './../data.js';
export default {
  name: "Group",
  components: {
    Item,
  },
  data(){
      return {
          Groups:Data
      }
  }
};
</script>

<style>
.group {
  flex-grow: 4; /* default 0 */
  width: 80%;
  margin: auto;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
}
</style>
