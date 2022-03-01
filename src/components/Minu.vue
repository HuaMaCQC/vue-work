<template>
  <div class="minu">
    <div class="pp">
      aaa
    </div>
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
.minu{
   width: 20vw;
   height: 30%;
   background: aquamarine;
   top: 150px;
   position: fixed;
   left: 0px;
   overflow: auto;
}
.pp{
  height: 2000px;
}
</style>