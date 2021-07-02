<template>
  <div class="bg-red-200 h-screen">
    <Banner/>
    <Modal/>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Modal from '../components/Modal.vue'
import Banner from '../components/Banner.vue'

export default Vue.extend({
  components: { Modal, Banner },})
</script>
