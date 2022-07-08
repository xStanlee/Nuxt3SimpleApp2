<template>
  <div>
    <Html lang="en-US">
      <Head>
        <Title>Restaurantly</Title>
        <Meta 
        name="description"
        content="Learn the stuff"/>
        <Link rel="preload" href="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQqfKhQ5AI4L3u9sJr7QRZUpOIcyS4Ok2kAmQ&usqp=CAU" as="script" />
      </Head>
    </Html>
    <div class="container mt-5"> 
      <h1> Welcome to Restaurantly </h1>
      <NuxtLink to="/restaurants">Go to restaurants</NuxtLink>
    </div>
  </div>
</template>
<style scoped>
.container {
  text-align: center;
}
</style>