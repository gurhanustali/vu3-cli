<template>
  <div class="container">{{title}}</div>
</template>

<script>
export default {
    props:[
        'title',
    ],
    data(){
        return {
            
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