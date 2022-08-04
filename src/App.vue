<script setup lang="ts">
import ArticleTest, { frontmatter } from './components/ArticleTest.md'
</script>

<template>
  <article-test />
  <p>
    frontmatter from component : {{ frontmatter }}
  </p>
</template>
