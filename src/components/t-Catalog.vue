<template>
    <div class="t-catalog">
        <h2>Catalog</h2>
        <t-catalog-item/>
    </div>
</template>
<script>
 import tCatalogItem from './t-CatalogItem';

export default {
   

    name: 't-Catalog',
        components: {
            tCatalogItem,
        },
        props: {},
        data() {
            return {
                title: 'Каталог'
            }
        },
        computed: {},
}
</script>
<style>
    .t-catalog {
        display: flex;
        flex-direction: column;
    }
</style>