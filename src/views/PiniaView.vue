<script setup lang="ts">
import { useCounterStore } from '@/stores/counter';

const counter = useCounterStore()
</script>
<template>
    <section class="flex gap2">
        <p>pinia实例：<span>{{ counter.count }}</span></p>
        <button @click="counter.increment">+</button>
    </section>
</template>