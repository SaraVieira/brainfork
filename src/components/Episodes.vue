<template>
  <div>
    <h1>Episodes</h1>
    <Hosts />
  </div>
</template>

<script>
import RSSParser from 'rss-parser';
import Hosts from './Hosts';
export default {
  components: {
    Hosts
  },
  name: 'HelloWorld',
  data() {
    return {
      episodes: []
    }
  },
  mounted() {
    let parser = new RSSParser();
    parser.parseURL('https://anchor.fm/s/576b8a8/podcast/rss', (_, feed) => {
      this.episodes = feed.items;
    })
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
</style>
