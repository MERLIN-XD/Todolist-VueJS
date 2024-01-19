<script setup>
import Table from './components/Table.vue';
const ToduList = [{s:'w'}];
</script>
<template>
  <div class="main-box">
    <div class="box">
      <div class="header">Todo List : บึกทึกกิจกรรม</div>
      <div class="body">
        <div class="body-full">
            <Table msg="{{ ToduList }}"></Table>
        </div>
      </div>
    </div>
  </div>
</template>
