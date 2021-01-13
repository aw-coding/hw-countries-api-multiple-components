<template lang='html'>
<div v-if='selectedCountry'>
    <h3>{{selectedCountry.name}}</h3>
    <h4>{{selectedCountry.population}}</h4> 
    <h4>{{selectedCountry.capital}}</h4>  
</div>
</template>

<script>
import {eventBus} from '../main.js'
export default {
    name: 'country-detail',
    props: ['country']   
};
</script>

<style lang='css'>

</style>