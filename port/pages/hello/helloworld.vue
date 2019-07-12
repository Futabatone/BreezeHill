<template>
  <section class="container">
    <div>
      <template>
    <h1>Hello {{ name }}!</h1>
  </template>

    </div>
  </section>
</template>

<script>
export default {
  data: () => {
    return { name: 'world' }
  }
}
</script>

<style>

</style>
