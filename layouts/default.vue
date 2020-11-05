<template>
  <section>
    <header class="header">
      <nav
        class="navbar has-shadow is-primary"
        role="navigation"
        aria-label="main navigation"
      >
        <div class="navbar-brand">
          <nuxt-link to="/" class="navbar-item">
            <h1 class="title">Blog</h1>
          </nuxt-link>
          <nuxt-link to="/" class="navbar-item ml-6">Início</nuxt-link>
          <nuxt-link to="/posts" class="navbar-item">Postagens</nuxt-link>

          <div class="navbar-burger">
            <span />
            <span />
            <span />
          </div>
        </div>
      </nav>
    </header>

    <section class="main-content columns mx-0">
      <div class="container column is-10">
        <nuxt />
      </div>
    </section>
  </section>
</template>

<script>
export default {}
</script>
