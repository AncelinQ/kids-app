<template>
  <center>
    <br />
    <h1>This is the Shop component</h1>
    <fileUpload></fileUpload>
  </center>
</template>

<script>
import FileUpload from '~/components/FileUpload/FileUpload.vue'
export default {
  components: {
    fileUpload: FileUpload,
  },
  data() {
    return {}
  },
}
</script>

<style scoped></style>
