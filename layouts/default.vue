<template>
  <section>
    <!-- Header -->
    <header class="header">
      <nav class="navbar has-background-info">
        <div class="navbar-brand">
          <nuxt-link to="/" class="navbar-item">
            <h1 class="title">Blog</h1>
          </nuxt-link>
        </div>

        <!-- Links Menu -->
        <div class="ml-6 is-flex wrap">
          <nuxt-link to="/" class="navbar-item">Início</nuxt-link>
          <nuxt-link to="/posts" class="navbar-item">Postagens</nuxt-link>
          <nuxt-link to="/authors" class="navbar-item">Autores</nuxt-link>
          <!-- Dropdown de opções -->
          <div class="navbar-item has-dropdown is-hoverable">
            <a class="navbar-link">Opções</a>

            <div class="navbar-dropdown mx-0">
              <!-- Link para criar postagem -->
              <nuxt-link to="/create-post" class="navbar-item"
                >Criar postagem
                <svg
                  version="1.1"
                  xmlns="http://www.w3.org/2000/svg"
                  xmlns:xlink="http://www.w3.org/1999/xlink"
                  viewBox="0 0 14.3 14.3"
                  xml:space="preserve"
                  height="1.7em"
                  class="ml-2"
                >
                  <path
                    style="fill: rgb(0, 0, 0)"
                    d="M3,9.8h6v1.5H3V9.8z M3,7.5V9h6V7.5H6.8H3z M3,5.3h6v1.5H3V5.3z M12,0h-1.5v2.3H8.3c0,0,0,1.5,0,1.5h2.3V6c0,0,1.5,0,1.5,0
	V3.8h2.3V2.3H12V0z M10.5,12.9h-9V3.8h5.3V2.3H1.5C0.7,2.3,0,2.9,0,3.8v9c0,0.8,0.7,1.5,1.5,1.5h9c0.8,0,1.5-0.7,1.5-1.5V7.5h-1.5
	V12.9z"
                  /></svg
              ></nuxt-link>
              <!-- Link para adicionar autor -->
              <nuxt-link to="/add-author" class="navbar-item"
                >Adicionar autor
                <svg
                  version="1.1"
                  xmlns="http://www.w3.org/2000/svg"
                  xmlns:xlink="http://www.w3.org/1999/xlink"
                  viewBox="0 0 16.5 12"
                  xml:space="preserve"
                  height="1.5em"
                  class="ml-2"
                >
                  <path
                    style="fill: rgb(0, 0, 0)"
                    d="M10.5,6c1.7,0,3-1.3,3-3s-1.3-3-3-3s-3,1.3-3,3S8.8,6,10.5,6z M3.8,4.5V2.3H2.3v2.3H0V6h2.3v2.3h1.5V6H6V4.5H3.8z M10.5,7.5
	c-2,0-6,1-6,3V12h12v-1.5C16.5,8.5,12.5,7.5,10.5,7.5z"
                  />
                </svg>
              </nuxt-link>
            </div>
          </div>
        </div>
      </nav>
    </header>

    <!-- Conteúdo -->
    <section class="main-content columns mx-0">
      <div class="container column is-10">
        <nuxt />
      </div>
    </section>
  </section>
</template>

<style>
.wrap {
  flex-wrap: wrap;
}
</style>

<script>
export default {}
</script>
