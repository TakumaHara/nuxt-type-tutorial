<template>
 <button type="button" @click="message">click</button>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
 name: 'Page',
 methods: {
   message() {
     const text: number = 99
     console.log(text)
   }
 }
})
</script>