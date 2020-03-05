<template>
  <section class="container-fluid">
    <div class="row">
      <div class="areaPhotoSize">
        <div class="blackmask font4">{{ title }}</div>
        <div class="areaPhotoLocation">
          <img :src="image" />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  props: {
    image: {
      type: String
    },
    title: {
      type: String
    }
  }
}
</script>

<style>
</style>
