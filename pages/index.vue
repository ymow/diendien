<template>
  <div>
    <NuxtLayout>
      <div class="container">
        <TheNavbar />
        <TheLanding />
        <div class="fb-like" data-share="true" data-width="450" data-show-faces="true">
        </div>
        <iframe
          src="https://www.facebook.com/plugins/video.php?height=476&href=https%3A%2F%2Fwww.facebook.com%2Finstagram%2Fvideos%2F493253239477286%2F&show_text=false&width=267&t=0"
          width="267" height="476" style="border:none;overflow:hidden" scrolling="no" frameborder="0"
          allowfullscreen="true" allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
          allowFullScreen="true"></iframe>
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