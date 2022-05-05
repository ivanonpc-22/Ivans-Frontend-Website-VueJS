<template>
  <div class="image-container" v-bind:class="rootClassName">
    <img :alt="image_alt" :src="image_src" class="image-image" />
  </div>
</template>

<script>
export default {
  name: 'Image',
  props: {
    image_src: {
      type: String,
      default:
        'data:image/svg+xml;base64,PHN2ZyB3aWR0aD0nMTEwNycgaGVpZ2h0PSc1ODUnIHZpZXdCb3g9JzAgMCAxMTA3IDU4NScgZmlsbD0nbm9uZScgeG1sbnM9J2h0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnJz4KPHJlY3QgeD0nMS4xMTU2MScgeT0nMS4xMTU3Nicgd2lkdGg9JzExMDQuODgnIGhlaWdodD0nNTgzLjM0Nycgcng9JzQuNjUyNzgnIGZpbGw9JyMwMTE2MjcnIHN0cm9rZT0nIzFFMkQzRCcgc3Ryb2tlLXdpZHRoPScwLjYyMDM3Jy8+Cjwvc3ZnPgo=',
    },
    rootClassName: String,
    image_alt: {
      type: String,
      default: 'Mainbackground641230',
    },
  },
}
</script>

<style scoped>
.image-container {
  display: flex;
  position: relative;
}
.image-image {
  width: 1106px;
  height: 584px;
  position: relative;
  object-fit: cover;
  border-color: rgba(30, 45, 61, 1);
  border-style: solid;
  border-width: 0.6203703284263611px;
  border-radius: 4.962962627410889px;
  background-color: rgba(1, 22, 39, 1);
}
</style>
