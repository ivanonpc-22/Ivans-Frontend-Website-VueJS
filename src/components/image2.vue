<template>
  <div class="image2-container" v-bind:class="rootClassName">
    <img :alt="image_alt" :src="image_src" class="image2-image" />
  </div>
</template>

<script>
export default {
  name: 'Image2',
  props: {
    image_src: {
      type: String,
      default:
        'data:image/svg+xml;base64,PHN2ZyB3aWR0aD0nMTExMCcgaGVpZ2h0PSc1ODcnIHZpZXdCb3g9JzAgMCAxMTEwIDU4NycgZmlsbD0nbm9uZScgeG1sbnM9J2h0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnJz4KPHJlY3QgeD0nMS4yNDQ0NicgeT0nMS4yNDQ0Nicgd2lkdGg9JzExMDguMTgnIGhlaWdodD0nNTg1LjA4OCcgcng9JzQuNjY2NjcnIGZpbGw9JyMwMTE2MjcnIHN0cm9rZT0nIzFFMkQzRCcgc3Ryb2tlLXdpZHRoPScwLjYyMjIyMicvPgo8L3N2Zz4K',
    },
    image_alt: {
      type: String,
      default: 'Mainbackground641715',
    },
    rootClassName: String,
  },
}
</script>

<style scoped>
.image2-container {
  display: flex;
  position: relative;
}
.image2-image {
  width: 1109px;
  height: 586px;
  position: relative;
  object-fit: cover;
  border-color: #ffffff;
  border-style: solid;
  border-width: 0.6222221851348877px;
  border-radius: 4.977777481079102px;
  background-color: rgba(1, 22, 39, 1);
}
</style>
