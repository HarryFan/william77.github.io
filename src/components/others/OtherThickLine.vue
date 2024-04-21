<script setup>
const { thick } = defineProps(['thick']);
</script>

<template>
    <div class="row dg-bg-0 dg-style"></div>
</template>

<style scoped>
.dg-style{
    height: v-bind(thick);
}
</style>