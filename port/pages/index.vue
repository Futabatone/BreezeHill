<!-- ./pages/index.vue -->
<template>
  <div>
    <section class="hero is-medium is-primary is-bold">
      <div class="hero-body">
        <app-logo/>
        <posts/>
        <div class="container">
          <h1 class="title">
            トップのタイトル
          </h1>
          <h2 class="subtitle">
            サブタイトル
          </h2>
        </div>
      </div>
      <div>
        トップだよ
      </div>
    </section>
  </div>
</template>

<script>
import Posts from '~/components/Posts.vue';
import AppLogo from '~/components/AppLogo.vue';


export default {
  components: {
    Posts,
    AppLogo
  },
}
</script>

<style>

</style>
