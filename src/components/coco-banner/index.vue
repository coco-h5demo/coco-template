<template>
  <a>
    哈哈哈--111
    <img
      :src="obj.src"
      width="100%"
      alt="图片"
    />
  </a>
</template>

<script>
export default {
  name: 'banner',
  props: {
    obj: {
      type: Object,
      default: () => {}
    }
  }
}
</script>
