<script setup>
    defineProps({
        datalist: String,
    })
</script>
<template lang="">
    <tr v-for="(item,index) in datalist" :key="index">
        <td width="10%">{{item.id}}</td>
        <td>{{item.name}}</td>
        <td width="30%">{{item.date}}</td>
        <td width="20%">
            <div class="btn btn-warning btn-sm">แก้ไข</div>&nbsp;
            <div class="btn btn-danger btn-sm">ลบ</div>
        </td>
    </tr>
</template>
<script>
export default {
    name: 'ItemVue',
}
</script>
<style lang="">
    
</style>