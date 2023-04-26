<template>
    <a-layout>
        <a-layout-header>
            <HeaderView></HeaderView>
        </a-layout-header>
        <a-layout-content>Content</a-layout-content>
        <a-layout-footer>Footer</a-layout-footer>
    </a-layout>
</template>


<script setup>
import HeaderView from '@/components/HeaderView/index.vue'

</script>

<style lang="less" scoped>
.ant-layout {
    .ant-layout-header {
        background-color: rgba(200, 200, 200, 0.7);
    }
}
</style>