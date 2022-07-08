<template>
  <div class="container mt-5"> 
    <NuxtLayout name="error">
      <template #header>
        <h1>Page not found</h1>
      </template>
      <template #redirect>
        <NuxtLink to="/restaurants">Go back</NuxtLink>
      </template>
    </NuxtLayout>
  </div>

</template>
<style scoped>
.container {
  text-align: center;
}
</style>