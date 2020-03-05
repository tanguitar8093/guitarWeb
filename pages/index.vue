<template>
  <section>
    <Carousel />
    <ImageBlocks />
    <DummySection title="全新 ＳＶ攻吉他 Youtuber" image="image/block0.jpg" />
    <Introduce />
    <DummySection title="聯大最狂最強吉他Youtuber" image="image/block0.jpg" />
    <PostSection />
  </section>
</template>

<script>
import Carousel from '~/components/Index/Carousel.vue'
import ImageBlocks from '~/components/Index/ImageBlocks.vue'
import Introduce from '~/components/Index/Introduce.vue'
import PostSection from '~/components/Index/PostSection.vue'
import DummySection from '~/components/UI/DummySection.vue'

export default {
  components: {
    Carousel,
    ImageBlocks,
    DummySection,
    PostSection,
    Introduce
  }
}
</script>

<style>
/* .container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
} */
</style>
