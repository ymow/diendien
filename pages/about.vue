<template>
  <div>
    <p>
      Hi, from {{ name }}
    </p>
    <nuxt-link to="/">Home Page</nuxt-link>
  </div>
</template>

<script>
  export default {
    layout: 'dark',
    data ({ req }) {
      return {
        name: req ? 'sever' : 'client'
      }
    }
  }
</script>