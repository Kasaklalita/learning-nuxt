<template>
  <div>
    <h2>Home</h2>
    <button @click="success" class="btn">click</button>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod fuga esse
      sit aperiam corporis modi fugit ducimus recusandae tempore quaerat!
    </p>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod fuga esse
      sit aperiam corporis modi fugit ducimus recusandae tempore quaerat!
    </p>
  </div>
</template>

<script setup>
import { useToast } from "vue-toastification";
const toast = useToast();

const success = () => toast.success("Hello!");
</script>

<style lang="scss" scoped></style>
