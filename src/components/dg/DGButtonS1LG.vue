<script setup>
import DGButtonTextLG from './DGButtonTextLG.vue';
</script>
<template>
<div class="dg-style dg-bg-primary1 dg-lh-3 dg-pl-16 dg-pr-16">
    <DGButtonTextLG class="dg-text-100"><slot></slot></DGButtonTextLG>
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