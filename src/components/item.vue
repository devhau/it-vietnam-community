<template>
  <div class="item">
    <h3>{{ data.title }}</h3>
    <h5>{{ data.info }}</h5>
    <h5>Zalo : <a :href=" data.link"> {{ data.link }}</a></h5>
  </div>
</template>

<script>
export default {
  name: "Item",
  props: ["data"],
};
</script>

<style>
.item {
  height: 300px;
  width: 300px;
  padding: 5px;
  border: 2px solid rgb(36, 67, 114);
  margin: 5px;
  background: #fff;
  color: rgb(36, 67, 114);
}
.item a{
  color: rgb(36, 67, 114);
}
</style>

