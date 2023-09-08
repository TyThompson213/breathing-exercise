<script setup lang="ts">
</script>

<template>
  <div class="scale-up-center"></div>
</template>

<style scoped>
.scale-up-center {
  border-radius: 100%;
  border: 1px solid rgb(152, 147, 255);
  background: rgb(152, 147, 255);
  width: 20rem;
  height: 20rem;
  box-shadow: 0px 0px 50px 10px rgb(152, 147, 255);
  -webkit-animation: scale-up-center 8s cubic-bezier(0.390, 0.575, 0.565, 1.000) infinite both;
  animation: scale-up-center 8s cubic-bezier(0.390, 0.575, 0.565, 1.000) infinite both;
}

@-webkit-keyframes scale-up-center {
  0% {
    -webkit-transform: scale(0.5);
    transform: scale(0.5);
  }

  50% {
    -webkit-transform: scale(1);
    transform: scale(1);
  }

  100% {
    -webkit-transform: scale(0.5);
    transform: scale(0.5);
  }
}

@keyframes scale-up-center {
  0% {
    -webkit-transform: scale(0.5);
    transform: scale(0.5);
  }

  50% {
    -webkit-transform: scale(1);
    transform: scale(1);
  }

  100% {
    -webkit-transform: scale(0.5);
    transform: scale(0.5);
  }
}</style>
