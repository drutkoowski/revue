<script setup>
import VueGridLayout from 'vue-grid-layout';
import ComponentsSidebar from '../../components/navigation/ComponentsSidebar.vue';
</script>

<template>
  <div>
    <p>HomeView</p>
    <ComponentsSidebar />
    <VueGridLayout.gridLayout
      ref="gridLayout"
      :layout.sync="layout"
      :col-num="12"
      :row-height="30"
      :is-draggable="true"
      :is-resizable="true"
    >
    </VueGridLayout.gridLayout>
  </div>
</template>
