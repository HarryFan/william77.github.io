<script setup>
import DGButtonTextSM from './DGButtonTextSM.vue';
</script>
<template>
<div class="dg-style dg-bg-primary3 dg-lh-1 dg-pl-16 dg-pr-16">
    <DGButtonTextSM class="dg-text-0"><slot></slot></DGButtonTextSM>
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