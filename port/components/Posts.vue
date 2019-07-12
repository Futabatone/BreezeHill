<template>
    <div>
    <h1>Hello {{ name }}!</h1>
    </div>
</template>

<script>
import users from '~/assets/posts.json';

export default {
  data: () => {
    return { name: 'world' }
    posts: posts
  }
}

</script>

<style>

</style>
