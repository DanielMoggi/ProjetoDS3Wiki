<script setup>
import MenuLateral from "@/components/MenuLateral.vue";
import CabecaLho from "@/components/CabecaLho.vue";

import { RouterView } from "vue-router";
</script>
<template>
  <CabecaLho />
  <RouterView />
  <MenuLateral />
</template>
<style></style>
