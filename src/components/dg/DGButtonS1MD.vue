<script setup>
import DGButtonTextMD from './DGButtonTextMD.vue';
</script>
<template>
<div class="dg-style dg-bg-primary1 dg-lh-2 dg-pl-16 dg-pr-16">
    <DGButtonTextMD class="dg-text-100"><slot></slot></DGButtonTextMD>
</div>
</template>
<style scoped>
.dg-style{
    display: inline-block;
    text-align: center;
    border-radius: 8px;
    cursor: pointer;
}
.dg-style:hover{
    opacity: 90%;
}
</style>