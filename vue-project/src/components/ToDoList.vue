<script setup>
  defineProps({
    msg2: {
      type: String,
      required: true
    }
  })
  </script>
<template>
  <div>
    <input type="checkbox" id="todo-item" />
    <label for="todo-item">{{ msg2 }}</label>
  </div>
</template>