<template>
<div>
      <pdf src="CV.pdf"></pdf>
      <!-- <router-link class="back-home" to="/">← Back home.</router-link> -->
  </div>
</template>

<script>
import pdf from 'vue-pdf'

export default {
  name: 'test',
  data () {
    return {
    }
  },
  components: {
    pdf
  }
}
</script>

<style scoped>
.bg {
  width: 100%;
  margin-bottom: 40px;
}

.back-home {
  font-weight: 700;
  font-size: 18px;
}

.back-home:hover {
  border: none;
}
</style>
