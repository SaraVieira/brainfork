<template>
  <div>
    <h1>Episodes</h1>
    <iframe src="https://anchor.fm/brainfuck/embed" height="150px" width="600px" frameborder="0" scrolling="no"></iframe>
    <Hosts />
  </div>
</template>

<script>
import Hosts from './Hosts'
export default {
  components: {
    Hosts
  },
  name: 'Episodes'
}
</script>
