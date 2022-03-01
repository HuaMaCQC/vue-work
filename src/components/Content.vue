<template>
  <div class="content">
    content
  </div>
</template>

<script>
import axios from 'axios';

axios({
  method: 'get',
  url: '127.0.0.1:9988/api/user',
})
  .then(function (response) {
    // handle success
    console.log(response);
  })
  .catch(function (error) {
    // handle error
    console.log(error);
  })


export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
