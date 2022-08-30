<template>
  <h1>Terms</h1>

</template>

<script>
export default {
  layout: 'dark',
  data({req}) {
    return {
      name: req ? 'sever' : 'client'
    }
  }
}
</script>