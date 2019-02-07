<template>
  <li>
    <h2>
      <a :href="artist.url" target="_blank">{{ artist.name }}</a>
      <img :src="artist.image[2]['#text']" alt>
    </h2>
  </li>
</template>

<script>
export default {
  name: "artist",
  props: ["artist"]
};
</script>

<style>
</style>