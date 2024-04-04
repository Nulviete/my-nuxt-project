<template>
    <div id="main">
        Hello      
    </div>

</template>

<script setup>
const response = await $fetch('/api/hello')
console.log(response.hello)


</script>
