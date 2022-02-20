<template>
  <ul class="list-group col-md-4">
    <VideoListItem v-for="video in myvideos" :video="video" :key="video.etag" @videoSelect="onVideoSelect">
    </VideoListItem>
  </ul>
</template>

<script>
import VideoListItem from "./VideoListItem";
export default {
  name: "VideoList",
  components: {
    VideoListItem,
  },
  props: ["myvideos"],
  methods: {
    onVideoSelect(video) {
      this.$emit('videoSelect', video);
    }
  }
};
</script>


