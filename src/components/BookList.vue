<template>
  <div>
    <h1>{{ title }}</h1>
  </div>
</template>

<script>
  export default {
    props: {
      name: String,
      title: String,
      data() {
        this.title = 'All Books';
        return this.title;
      }
    },
  }
</script>

<style>
  h1, h2 {
    font-weight: normal;
  }
</style>
