<!-- Please remove this file from your project -->
<template>
  <div>
    <div>
      {{ count }}
    </div>
    <button @click="incrementCount">+</button>
    <button @click="decrementCount">-</button>
  </div>
</template>
<script>
export default {
  data() {
    return {
      count: 0,
    }
  },
  methods: {
    incrementCount:  function() {
      this.count++
    },

    decrementCount: function() {
      this.count--
    },

  }
}
</script>