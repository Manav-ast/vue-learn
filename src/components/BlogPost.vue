<!-- <script setup>
defineProps(['title']);
</script>

<template>
  <h2>{{ title }}</h2>
</template> -->


<script setup>
defineProps(['id', 'title'])
// defineProps(['title'])
defineEmits(['enlarge-text'])
</script>

<template>
  <div class="blog-post">
    <h3>Blog Post {{ id }}</h3>
    <h3>{{ title }}</h3>
    <button @click="$emit('enlarge-text')">Enlarge text</button>
  </div>
</template>