<template>
  <div>
    <NuxtLayout>
      <div class="container">
        <TheNavbar />
        <TheLanding />
        <div
            class="fb-like"
            data-share="true"
            data-width="450"
            data-show-faces="true">
        </div>
<!--        <h1>Welcome</h1>-->
<!--        <nuxt-link to="/about">About</nuxt-link>-->
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