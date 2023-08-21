<template>  
  <div>
    <h2>About</h2>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab quaerat tenetur voluptate ratione quod exercitationem? Amet blanditiis voluptas at assumenda.</p>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Vero rerum in repellat eos accusamus nisi natus dolorem eius exercitationem optio perspiciatis officia, voluptatibus quisquam numquam error itaque. Reprehenderit voluptatem cumque nostrum expedita placeat sed! Obcaecati tenetur eaque qui excepturi error odit in dignissimos, consectetur maiores sapiente natus, numquam asperiores voluptatem!</p>
    <div>{{ data }}</div>
  </div>
</template>

<script setup>
  const { data } = await useFetch('/api/currency/GBP')
</script>

<style scoped>
h2{
  margin-bottom: 20px;
  font-size: 36px;
}
p{
  margin: 20px 0;
}
</style>