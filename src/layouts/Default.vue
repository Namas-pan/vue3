<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
// import MyHeader from '@/components/MyHeader.vue';
// import MyFooter from '@/components/MyFooter.vue';

</script>
<template>
    <div class="w-screen h-screen flex flex-col justify-between items-center">
        <MyHeader></MyHeader>
        <RouterView></RouterView>
        <MyFooter></MyFooter>
    </div>
</template>