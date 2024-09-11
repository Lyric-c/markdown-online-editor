<!-- @format -->

<template>
  <PreviewVditor :pdata="pdata" @callback="handleCallBack" />
</template>

<script>
import PreviewVditor from '@components/PreviewVditor'

export default {
  name: 'markdown',

  data() {
    return {
      isLoading: false,
    }
  },

  created() {},

  components: {
    PreviewVditor
  },

  mounted() {},

  methods: {
    handleCallBack() {
      this.isLoading = false
    }
  }
}
</script>