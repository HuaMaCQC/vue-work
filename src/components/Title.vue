<template>
  <div class="title">
      Title
  </div>
</template>

<script>
export default {
  name: "HeadA",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.title{
   width: 100%;
   height: 150px;
   background: red;
   top: 0px;
   position: fixed;
}
</style>