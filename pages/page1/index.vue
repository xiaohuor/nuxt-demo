<template>
  <div>
    <h1>page1</h1>
    <div>pageId: {{$route.params.id}}</div>
    <nuxt-link :to="{name: 'index'}">back to Home</nuxt-link>
    <ul>
      <li>
        <nuxt-link :to="{name: 'page1-id', params: {id: 123}}">item1</nuxt-link>
      </li>
      <li>
        <nuxt-link :to="{name: 'page1-id', params: {id: 456}}">item2</nuxt-link>
      </li>
    </ul>
  </div>
</template>

<script>
  export default {
  }
</script>

<style scoped>

</style>