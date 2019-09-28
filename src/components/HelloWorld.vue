<template>
  <div>
    Hello World
    <p>{{message}}</p>
    <p>{{saurav}}</p>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      message: "Life is Beautiful!!",
      saurav: "No its not"
    };
  }
};
</script>

<style lang="stylus" scoped></style>