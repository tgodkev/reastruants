<template>
  <main class="mx-auto lg:max-w-6xl px-5 pt-6 pb-6">
    <div class="container">
      <NuxtLayout name="error">
        <template #header>
          <h1>page not found.</h1>
        </template>

        <template #redirectEl>
          <NuxtLink to="/">Go Back</NuxtLink>
        </template>
      </NuxtLayout>
    </div>
  </main>
</template>


<style scoped>
.container {
  text-align: center;
  margin-top: 5rem;
}
</style>

