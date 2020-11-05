<template>
  <div class="column">
    <div class="card">
      <div class="card-header">
        <h1 class="card-header-title">{{ title }}</h1>
      </div>
      <div class="card-content">{{ description }}</div>
      <div class="card-footer">
        <div v-if="author" class="card-footer-item">
          <p class="text"><strong>Criado por: </strong>{{ author }}</p>
        </div>
        <div class="card-footer-item">
          <p class="text"><strong>Data da postagem: </strong> {{ date }}</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      required: true,
      default: '',
    },
    description: {
      type: String,
      required: true,
      default: '',
    },
    author: {
      type: String,
      required: false,
      default: '',
    },
    date: {
      type: String,
      required: true,
      default: '',
    },
  },
}
</script>
