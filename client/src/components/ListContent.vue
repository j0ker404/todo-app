<template>
  <div id="lsContent">
    <ListItem v-bind:itemData="data[2]"/>
  </div>
</template>

<script>

import ListItem from './ListItem.vue'
export default {
    name: 'ListContent',
    components: {
      ListItem
    },

    props: ['data']
}
</script>

<style scoped>

</style>