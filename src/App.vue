<script setup lang="ts">
import AppLayout from './components/AppLayout.vue'

const appName = 'Recipe Book'
const menuItems = [{ link: '/', label: 'Home' }]
</script>

<template>
  <AppLayout :appName="appName" :menuItems="menuItems">
    <template #default>
      <div class="test-content">
        <p>Neuer Test</p>
      </div>
    </template>
  </AppLayout>
</template>

<style scoped>
.test-content {
  padding: 16px;
  text-align: center;
}
</style>
