<script setup>
import headerVue from './components/header.vue'
import mainVue from './components/main.vue'
import footerVue from './components/footer.vue';
import subFooterVue from './components/subFooter.vue';
</script>

<template>
    <headerVue></headerVue>
    <mainVue></mainVue>
    <footerVue></footerVue>
    <subFooterVue></subFooterVue>
</template>

<style lang="scss" scoped>
body{
    @import url('https://fonts.googleapis.com/css2?family=Open+Sans&display=swap');
}
</style>
