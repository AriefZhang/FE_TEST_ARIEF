<script setup>
import { RouterView } from "vue-router";
</script>

<template>
  <RouterView />
  <audio controls autoplay loop ref="bgAudio" hidden>
    <source src="@/assets/audio/Beginning_DreamXyla.mp3" type="audio/mpeg">
    Your browser does not support the audio tag.
  </audio>
</template>
