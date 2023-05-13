<script setup lang="ts">
import { RouterLink } from 'vue-router';

const head_path = ref([
    { name: 'index', path: '/index', id: 1 },
    { name: 'pinia', path: '/pinia', id: 2 },
    { name: 'pinia示例', path: '/PiniaExample', id: 3 },
])

</script>
<template>
    <main class="w-screen ">
        <nav class="flex h-10 items-center gap-2 ">
            <img src="" alt="" class="w-8 h-8 bg-red rounded-1/2 cursor-pointer">
            <div v-for="item in head_path" :key="item.id">
                <RouterLink :to="item.path">
                    {{ item.name }}
                </RouterLink>
            </div>
        </nav>
    </main>
</template>