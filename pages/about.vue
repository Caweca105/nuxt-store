<template>
  <div>
    <h2>About</h2>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Reiciendis
      error, itaque inventore sunt assumenda, accusantium sed distinctio animi
      amet vero aperiam suscipit ut! Nostrum eius mollitia adipisci, veritatis
      praesentium veniam.
    </p>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Pariatur ullam
      velit consectetur consequatur totam quos, quam omnis corrupti. Nesciunt,
      rem delectus. Eaque expedita rem architecto vitae rerum animi, est optio?
    </p>

    <div>{{ data }}</div>
  </div>
</template>

<script setup>
const { data } = await useFetch("/api/currency/GBP");
</script>

<style scoped>
h2 {
  margin-bottom: 20px;
  font-size: 36px;
}
p {
  margin: 20px 0;
}
</style>
