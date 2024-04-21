<script setup>
import DGTextBody from './components/dg/DGTextBody.vue';
import DGTextH1 from './components/dg/DGTextH1.vue';
import OtherThickLine from './components/others/OtherThickLine.vue';
</script>

<template>
  <header class="container-fluid ">
    <OtherThickLine thick="8px"/>
    <div class="row">
      <div class="col dg-lh-5">
        <DGTextH1>William77 Design Guideline </DGTextH1>
        <DGTextBody>Webpage Version</DGTextBody>
      </div>
      <div class="col dg-lh-5 dg-pr-56 text-end">
        <RouterLink to="/" class="dg-p-16 text-decoration-none"><DGTextBody>Home</DGTextBody></RouterLink>
        <RouterLink to="/sample" class="dg-p-16 text-decoration-none"><DGTextBody>Sample</DGTextBody></RouterLink>
        <RouterLink to="/about" class="dg-p-16 text-decoration-none"><DGTextBody>About</DGTextBody></RouterLink>
      </div>
    </div>
  </header>
  <hr class="dg-m-0">
  <RouterView />
</template>