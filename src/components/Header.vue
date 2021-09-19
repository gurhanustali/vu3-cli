<template>
  <div class="container">{{title}}</div>
</template>

<script>
export default {
    data(){
        return {
            title:"This is header."
        }
    }
}
</script>

<style scoped>
    div{
        background-color: blueviolet;
        color: white;
        font-size: x-large;
    }
</style>