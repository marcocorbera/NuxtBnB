<template lang="html">
  <div class="">
  <img :src="home.images[0]" style="width: 200px"><br/>
  {{ home.titte }} <br/>
  {{ home.location.address }} {{ home.location.city }} {{ home.location.state }}<br/>
  {{ home.guests }} guests<br/>
  {{ home.pricePerNight}} / Night<br/>
  </div>
</template>

<script>
export default {
  props: {
    home: {
      type: Object,
      required: true
    }
  }
}
</script>

<style lang="css" scoped>
</style>
