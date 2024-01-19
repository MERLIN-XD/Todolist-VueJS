<script setup>
    import ItemVue from "./ItemVue.vue";
    defineProps({
        msg: String,
    })
</script>
<template lang="">
    <div>
        <table>
                <thead>
                  <th>ลำดับ</th>
                  <th>รายการ</th>
                  <th>วันเวลา</th>
                  <th>Action</th>
                </thead>
                <tbody>
                  <ItemVue datalist="{{ msg }}"/>
                </tbody>
            </table>
    </div>
</template>