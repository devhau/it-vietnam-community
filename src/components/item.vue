<template>
  <div class="item">
    <div class="box">
      <h3>{{ data.title }}</h3>
      <h5>{{ data.info }}</h5>
      <h5>Zalo : <a :href=" data.link"> {{ data.link }}</a></h5>
    </div>
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
  height: 200px;
  width: 23.5%;
  padding: 5px;
  margin: 0;
}
.item .box{  
  border: 2px solid rgb(36, 67, 114);
  background: #fff;
  color: rgb(36, 67, 114);
  height: 100%;
}
@media only screen and (max-width: 768px) {
  .item {
    width: 100%;
  }
}
@media only screen and (min-width: 768px) and (max-width: 1000px) {
  .item {
    width: 48%;
  }
}
.item a {
  color: rgb(36, 67, 114);
}
</style>

