<template lang="html">
  <div v-if="country">
    <h3>{{country.name}}</h3>
    <p>{{country.capital}}</p>
    <p>{{country.population}}</p>


  </div>

</template>

<script>
export default {
  name: 'country-details',
  props: ['country']
}
</script>

<style lang="css" scoped>
</style>
