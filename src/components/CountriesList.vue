<template>
<div>
<ul>
<list-country v-for='(country, index) in countries' :country='country' :key='index'></list-country>
</ul>
</div>
</template>

<script>
import ListCountry from './ListCountry.vue';

export default {
    name: 'countries-list',
    props: ['countries'],
    components: {
        "list-country": ListCountry
    }
    
}

</script>


<style>

</style>