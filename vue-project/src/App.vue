<template>
<h3>{{ info }}</h3>
<p> {{ someInfo }} </p>
<buttom type="button" @click="userData('Text')">Отправить</buttom>
</template>

<style scoped>
h3 {
  color: red;
  font-weight: lighter;
}
p {
  color: blue;
  font-weight: bold;
}
</style>

<script lang="ts">

export default {
  data() {
    return {
      info: "Title",
      someInfo: "Anons of message"
    }
  },
  methods: {
    userData(word = "New text") {
      this.someInfo = word
    }
  }
}
</script>
