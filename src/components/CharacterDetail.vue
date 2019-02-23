<template lang="html">
<div v-if ="character">

  <h1>{{character.name}}</h1>
  <p>House: {{character.house}}</p>
  <p>Ancestry :{{character.ancestry}}</p>
  <img :src="character.image" :alt="character.name">
</div>


</template>

<script>
export default {
  name: 'character-detail',
  props: ["character"]
}
</script>

<style lang="css" scoped>
</style>
