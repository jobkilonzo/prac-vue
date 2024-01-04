<script setup>
import { store } from './store';

</script>

<template>
    <p>From component A: {{ store.count }}</p>
    <button @click="store.increment">Count: {{ store.count }}</button>
</template>