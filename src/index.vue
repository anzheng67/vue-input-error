<template>
  <div class="pz-input-error" v-if="error.active"> 
    <strong>{{ error.code }}</strong>
    {{ error.message }}
  </div>
</template>

<script>
export default {
  props: ['error']
}
</script>

<style src="./style.css"></style>
