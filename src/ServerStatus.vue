<template>
  <div>
    <h3>Server status: {{ status }}</h3>
    <hr>
    <button @click="changeServerStatus">Change Server Status</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      status: 'OK'
    }
  },

  methods: {
    changeServerStatus() {
      this.status = 'BAD'
    }
  }
}
</script>
