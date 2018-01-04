<template>
  <section class="container">
    <div>
      <h1 class="title">
        Bot Setup
      </h1>
      <h3 class="subtitle">
        This explicit interactive guide will tell you all about setting up your development
        environment.
      </h3>
      <nuxt-link to="/1">Start the Guide</nuxt-link>
    </div>
  </section>
</template>

<style scoped>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #ecf0f1;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #bdc3c7;
  word-spacing: 5px;
  padding-bottom: 15px;
}
</style>
