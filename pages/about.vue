<template>
  <div>
    <h2>About</h2>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod fuga esse
      sit aperiam corporis modi fugit ducimus recusandae tempore quaerat!
    </p>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod fuga esse
      sit aperiam corporis modi fugit ducimus recusandae tempore quaerat!
    </p>
    <div>{{ data }}</div>
  </div>
</template>

<script setup>
const { data } = await useFetch("/api/ninja?name=Veniamin", {
  method: "post",
  body: { age: 18 },
});
</script>

<style lang="scss" scoped></style>
