<template>
  <div id="blog-post-demo">
    <blog-post title="My journey with Vue"></blog-post>
    <blog-post title="Blogging with Vue"></blog-post>
    <blog-post title="Why Vue is so fun"></blog-post>
    <!-- <h3>{{ title }}</h3> -->
  </div>
</template>


<script>
  export default {
    name: 'basic',
    data: function () {
      return {
        posts: [
          { id: 1, title: 'My journey with Vue' },
          { id: 2, title: 'Blogging with Vue' },
          { id: 3, title: 'Why Vue is so fun' }
        ]
      }
    },
    props: {
      titl: String,
    },
  }
</script>









<!--

<template>
  <div>
    <button @click="count++">{{ titl }} Счётчик кликов — {{ count }}</button>
  </div>
</template>



<script>
  export default {
    name: 'basic',
    data: function () {
      return {
        count: -1,
      }
    },
    props: {
      titl: String,
    },
  }
</script>

-->
