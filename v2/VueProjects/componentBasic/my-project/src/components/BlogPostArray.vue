<template>
  <h3>{{ post }}</h3>
</template>

<script>
  export default {
    name: 'blog-post-array',
    post : [
      { id: 1, title: 'My journey with Vue' },
      { id: 2, title: 'Blogging with Vue' },
      { id: 3, title: 'Why Vue is so fun' }
    ]
  }
</script>