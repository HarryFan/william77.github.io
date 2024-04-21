<script setup>
import DGButtonTextLG from './DGButtonTextLG.vue';
</script>
<template>
<div class="dg-style2 dg-bg-100 dg-lh-3 dg-pl-16 dg-pr-16">
    <DGButtonTextLG class="dg-text-primary1"><slot></slot></DGButtonTextLG>
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