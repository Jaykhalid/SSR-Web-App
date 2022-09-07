<template>
  <main>
    <Nuxt/>
    <h1>Home page</h1>
    <NuxtLink to="/about">
      About (internal link that belongs to the Nuxt App)
    </NuxtLink>
    <a href="https://nuxtjs.org">External Link to another page</a>
  </main>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
