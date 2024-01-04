<script setup>
import { store } from './store';

</script>

<template>
    <p>From component B: {{ store.count }}</p>
    <button @click="store.count++">Count: {{ store.count }}</button>
</template>