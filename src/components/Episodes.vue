<template>
  <div>
    <h1>Subscribe on:</h1>
    <ul>
      <!-- <li>
        <a href="https://anchor.fm/brainfork" target="_blank"><img src="../assets/anchor.png" /></a>
      </li> -->
      <li>
        <a href="https://www.google.com/podcasts?feed=aHR0cHM6Ly9hbmNob3IuZm0vcy81NzZiOGE4L3BvZGNhc3QvcnNz" target="_blank"><img src="../assets/googleplay.svg" /></a>
      </li>
      <li>
        <a href="https://open.spotify.com/show/73noaRvYRWQOf69I4itkZZ" target="_blank"><img src="../assets/spotify.svg" /></a>
      </li>
      <li>
        <a href="https://pca.st/5TlB" target="_blank"><img src="../assets/pocketcasts.png" /></a>
      </li>
      <li>
        <a href="https://play.radiopublic.com/brainfork-6Lamgz" target="_blank"><img src="../assets/radiopublic.png" /></a>
      </li>
    </ul>
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
<style lang="scss" scoped>
.episode {
  height: 150px;
  width: 770px;
  max-width: 100%;
}

ul {
  list-style: none;
  margin: 0 auto;

  li {
    display: inline;

    &:not(:last-child) {
      margin-right: 10px;
    }

    img {
      width: 40px;
    }
  }
}
</style>
