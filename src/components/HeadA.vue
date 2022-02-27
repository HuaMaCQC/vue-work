<template>
  <div class="Head">
    這是HEAD
    <div class="bb" id="666">
      這是BB
      <div class="cc">這是BB 裡面的CC</div>
    </div>
    <div class="cc bb">這是BB 外面的CC</div>

    <div>
      <b-button>Button</b-button>
      <b-button variant="danger">Button</b-button>
      <b-button variant="success">Button</b-button>
      <b-button variant="outline-primary">Button</b-button>
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
</style>