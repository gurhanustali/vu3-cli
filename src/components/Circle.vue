<template>
  <span class="dot" :style="setBackColor" @mouseover="mouseOver()"></span>
</template>

<script>
export default {
    data(){
        return {
            hover:false,
        }
    },
    props:[
        'color',
    ],
    methods:{
        mouseOver(){
            this.hover=!this.hover;
            console.log(this.hover);
        }
    },
    computed:{
        setBackColor(){
            return 'background-color: '+(this.hover?this.color:"gray");
        }
    }

}
</script>

<style scoped>
.dot {
  height: 25px;
  width: 25px;
  background-color: gray;
  border-radius: 50%;
  display: inline-block;
}
</style>