<script setup lang="ts">
import { useCounterStore } from '@/stores/counter';

const counter = useCounterStore()
</script>
<template>
    <section>
        <div>
            <p>计数器结果: <span>{{ counter.count }}</span> </p>
        </div>
    </section>
</template>