<template>
  <div>
    <TheNavbar />
    <span class="test">
    </span>
    <Nuxt />
  </div>
</template>

<script setup>

</script>
  window.fbAsyncInit = function() {
  FB.init({
  appId      : '589360812636679',
  xfbml      : true,
  version    : 'v14.0'
  });
  FB.AppEvents.logPageView();
  };

  (function(d, s, id){
  var js, fjs = d.getElementsByTagName(s)[0];
  if (d.getElementById(id)) {return;}
  js = d.createElement(s); js.id = id;
  js.src = "https://connect.facebook.net/en_US/sdk.js";
  fjs.parentNode.insertBefore(js, fjs);
  }(document, 'script', 'facebook-jssdk'));
<style lang="sass" scoped>
div
  .test
    color: red
</style>