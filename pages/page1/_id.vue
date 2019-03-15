<template>
  <div>
    <h1>list</h1>
    <nuxt-link :to="{name: 'page1'}">back to Page1</nuxt-link>
    <div>listId: {{$route.params.id}}</div>
  </div>
</template>

<script>
  export default {
    transition: 'list',
    validate({params}) {
      return /^\d+$/.test(params.id)
    }
  }
</script>