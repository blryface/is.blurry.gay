<template>
    <title> Yes. </title>
    <div class="a"></div>
</template>

<style>

.a {
    font-family: sans-serif;
}

</style>
  
<script>
  export default {
    async setup() {
    if (true) {
      throw createError({
        statusCode: 420,
        fatal: false,
        message: "Enhance your calm.",
      })
    }
  }  }
</script>