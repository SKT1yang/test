<template>
  <config-provider
    :theme="{
      algorithm: theme.darkAlgorithm,
    }"
  >
    <App>点击</App>
  </config-provider>
</template>

<script setup lang="ts">
  import { theme, ConfigProvider } from 'ant-design-vue';
  import {App} from 'antdv-component-test'
</script>
