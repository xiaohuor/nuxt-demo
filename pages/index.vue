<template>
  <div>
    <h1>home</h1>
    <ul>
      <li>
        <nuxt-link :to="{name: 'page1', params:{id: 12}}">page1</nuxt-link>
      </li>
      <li>
        <nuxt-link :to="{name: 'page2'}">page2</nuxt-link>
      </li>
    </ul>
  </div>
</template>

