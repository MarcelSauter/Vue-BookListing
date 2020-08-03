<template>
  <div>
    <li v-for="book in books">{{ book.title }}:{{ book.author }}</li>
  </div>
</template>

<script>
  export default {
    name: 'BookItem',
    props: ['book']
  }
</script>

<style>

</style>
