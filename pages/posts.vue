<template>
  <section class="section mx-0">
    <h1 class="title has-text-centered">Postagens recentes</h1>
    <section class="section mx-0">
      <div class="columns mx-0">
        <Card
          title="Um diaaa"
          description="Lorem, ipsum dolor sit amet consectetur adipisicing elit. Fuga eos vero dolor fugiat! Culpa, architecto impedit voluptatibus earum libero optio."
          author="Matheus"
          date="05/11/2020"
        />
      </div>
    </section>
  </section>
</template>

<script>
import Card from '../components/Card'
export default {
  components: {
    Card,
  },
}
</script>
