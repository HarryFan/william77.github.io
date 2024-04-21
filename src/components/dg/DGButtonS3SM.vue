<script setup>
import DGButtonTextSM from './DGButtonTextSM.vue';
</script>
<template>
<div class="dg-style2 dg-bg-100 dg-lh-1 dg-pl-16 dg-pr-16">
    <DGButtonTextSM class="dg-text-primary1"><slot></slot></DGButtonTextSM>
</div>
</template>
<style scoped>
.dg-style2{
    display: inline-block;
    text-align: center;
    border-radius: 8px;
    border: 4px solid var(--dg-color-primary1);
    cursor: pointer;
}
.dg-style2:hover{
    opacity: 90%;
}
</style>