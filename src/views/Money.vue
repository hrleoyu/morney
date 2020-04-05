<template>
    <div class="nav-wrapper">
        <div class="content">
            money.vue
        </div>
        <hr/>
        <Nav/>
    </div>
</template>


<script lang="ts">
    import Vue from 'vue'
    import Nav from '@/components/Nav.vue'

    export default Vue.extend({
        name: 'Money',
        components: {Nav}
    })
</script>


<style lang="scss" scoped>
    .nav-wrapper{
        border: 1px solid green;
        display: flex;
        flex-direction: column;
        height: 100vh;
    }
    .content {
        overflow: auto;
        flex-grow: 1;
    }
</style>