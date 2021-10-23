<template>
  <div class="gallery">
    <div class="gallery-modal" :style="GalleryModalStyle">
      <div :style="displayBlock" class="gallery-closer" @click="closeModal(this)">×</div>
      <div :style="displayBlock" class="gallery-prev" @click="prevSlide(this)">❮</div>
      <div class="gallery-slide" :style="slideImageStyle" @click="showModal"></div>
      <div :style="displayBlock" class="gallery-next" @click="nextSlide(this)">❯</div>
    </div>
    <div class="gallery-thumb">
      <img
        v-for="(image, idx) in images"
        :key="idx"
        :src="image"
        :class="{active: idx == activeIndex}"
        @click="activeIndex = idx"
      />
    </div>
  </div>
</template>

<script>
export default {
  props: {
    images: {
      type: Array,
      default: () => []
    }
  },
  data() {
    return {
      activeIndex: 0,
      isModalShow: false
    }
  },
  computed: {
    slideImageStyle() {
      let style = {}
      if (this.isModalShow) {
        style = {
          cursor: 'default',
          backgroundSize: 'contain',
          height: '90%'
        }
      }
      style.backgroundImage = "url('" + this.images[this.activeIndex] + "')"

      return style
    },
    GalleryModalStyle() {
      if (this.isModalShow) {
        return {
          backgroundColor: 'rgba(0, 0, 0, 0.933)',
          position: 'fixed',
          display: 'flex',
          height: '100vh',
          zIndex: '9999',
          margin: '0px'
        }
      } else {
        return {}
      }
    },
    displayBlock() {
      if (this.isModalShow) {
        return { display: 'block' }
      } else {
        return {}
      }
    }
  },
  methods: {
    showModal() {
      this.isModalShow = true
    },
    closeModal() {
      this.isModalShow = false
    },
    nextSlide() {
      if (this.activeIndex + 1 < this.images.length) {
        this.activeIndex++
      }
    },
    prevSlide() {
      if (this.activeIndex > 1) {
        this.activeIndex--
      }
    }
  }
}
</script>

<style>
</style>