<template>
  <div class="home-page">
    <TextTransparencyBlock />
  </div>
</template>

<script>
import TextTransparencyBlock from '@/components/TextTransparencyBlock'

export default {
  name: "Homepage",
  components: {
    TextTransparencyBlock
  }
}
</script>

<style>
.home-page {
  width: 100%;
  height: auto;
}
</style>
