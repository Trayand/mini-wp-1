<template>
  <div class="ui search">
    <div class="ui icon input">
      <input class="prompt" type="text" placeholder="Search tag..." v-model="$root.tagSearch" />
      <i class="search icon"></i>
    </div>
    <div class="results"></div>
  </div>
</template>

<script>
export default {
  name: "TagSearch"
};
</script>

<style>
</style>