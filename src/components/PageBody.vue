<template>
    <div id="body-container">
      <page-greeting></page-greeting>
      <page-hook></page-hook>
      <page-image></page-image>
    </div>
</template>

<script>
import PageGreeting from './PageGreeting.vue';
import PageHook from './PageHook.vue';
import PageImage from './PageImage.vue';
    export default {

        components: {
             PageGreeting,
             PageHook,
             PageImage,
        },
       
    }
</script>

<style scoped>
#body-container {
    width: 100%;
    min-height: 80vh;
    background: honeydew;
}
</style>