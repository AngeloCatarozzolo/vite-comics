<script setup>
import headerVue from './components/header.vue'
import mainVue from './components/main.vue'
import footerVue from './components/footer.vue';
</script>

<template>
    
    <div class="section">
        <headerVue></headerVue>
    </div>
    <div>
        <mainVue></mainVue>
    </div>
</template>

<style lang="scss" scoped>

#app{
    padding: 0;
    margin: 0;
    width: 100%;
}
.section{
    width: 100%;
    display: flex;
}
</style>
