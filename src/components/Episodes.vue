<template>
  <div>
    <h1>Episodes</h1>
    <iframe src="https://anchor.fm/brainfork/embed" class="episode" frameborder="0" scrolling="no"></iframe>
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
<style>
 .episode {
    height: 150px;
    width: 770px;
    max-width: 100%;
 }

</style>
