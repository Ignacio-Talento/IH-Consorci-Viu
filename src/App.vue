<script setup>
import ConditionalRendering from './components/ConditionalRendering.vue';
import HeaderComponent from './components/HeaderComponent.vue';
import InputComponent from './components/InputComponent.vue';
import ListComponent from './components/ListComponent.vue';
import ParentComponent from './components/ParentComponent.vue';
import ProductList from './components/ProductList.vue';
import VariablesComponent from './components/VariablesComponent.vue';

</script>

<template>
  <HeaderComponent />

  <h1>Hola a todos!</h1>
  
  <VariablesComponent />
  <InputComponent />
  <ConditionalRendering />
  <ListComponent />
  <ProductList />
  <ParentComponent />
</template>

<style>
</style>