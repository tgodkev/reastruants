<template>
  <div>
    <Html :lang="dynamic > 50 ? 'en-GB' : 'en-US'">
    <Head>
      <!--      can change title per page -->
      <Title>Restrauntly</Title>
      <!--      add meta data to each page if needed -->
      <Meta content="my page is awesome" name="description"></Meta>
      <!--      ability to change favicon per page in the link tag-->
      <Link as="script" href="" rel="preload"/>
    </Head>
    </Html>

    <div class="container">
      <h1>Welcome to Restaurantly</h1>
      <NuxtLink to="/restaurants">Go to restaurants</NuxtLink>
    </div>

  </div>
</template>


<style scoped>
.container {
  text-align: center;
  margin-top: 5rem;
}

</style>
