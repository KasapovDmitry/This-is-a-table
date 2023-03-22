<template>
    <div class="t-main">
        <h2>{{ title }}</h2>
        <t-catalog/>
        <t-item/>
    </div>
</template>
   
<script>
import tCatalog from './t-Catalog';
import tItem from './t-Item';


    export default {
        name: 't-Main',
        components: {
            tCatalog,
            tItem
        },
        props: {},
        data() {
            return {
                title: 'Каталог'
            }
        },
        computed: {},
        methods: {},
        watch: {},
        mounted() {
            console.log('HELLO VUE!!!')
        }
    }
</script>
   
<style>
    .t-main {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }
</style>
   