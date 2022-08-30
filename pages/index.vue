<template>
  <div>
    <NuxtLayout>
      <div class="container">
        <TheNavbar />
        <TheLanding />
        <h1>Welcome</h1>
        <nuxt-link to="/about">About</nuxt-link>
      </div>
    </NuxtLayout>
  </div>

</template>

<script setup>
import TheLanding from "@/components/TheLanding";
import TheNavbar from "@/components/TheNavbar";
</script>

<style>

</style>