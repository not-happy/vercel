<template>
  <div class="main">
    <div class="head">
      <h1>head</h1>
    </div>
    <div class="content">
      <div class="left">
        left
      </div>
      <div class="right">
        right
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.main {
  display: flex;
  flex-direction: column;
  border: 1px solid #8fb942;
}
.head {
  width: 100%;
  height: 200px;
  border: 1px solid #fc052a;
}
.content {
  width: 100%;
  display: flex;
  flex-direction: row;
  border: 1px solid #0033ff;
}
.left {
  width: 60%;
  border: 1px solid #010101;
}
.right {
  width: 40%;
  border: 1px solid #ee08b8;
}
</style>
