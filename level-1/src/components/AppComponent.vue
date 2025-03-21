<template>
  <h1>{{ title }}</h1>
  <p>{{ text }}</p>
</template>

<script>
export default {
  data() {
    return {
      text: "Come back often"
    };
  },
  props: {
    title: String,
  },
};
</script>

<style lang="scss" scoped>
h1 {
  color: #42b983;
  margin: 0;
}
p{
  color: #202020;
  font-size: 32px;
  margin: 4px 0 0;
}
</style>
