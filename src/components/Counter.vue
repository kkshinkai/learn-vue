<template>
  <button @click="count++" :style="exampleStyle">Count is: {{ count }}</button>
</template>

<script>
export default {
  data() {
    return {
      count: 0,
      exampleStyle: {
        color: 'red',
        fontSize: '2em'
      }
    }
  }
}
</script>
