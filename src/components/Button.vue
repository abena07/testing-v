<template>
  <buttton @click="onClick()" :style="{background:color }" class="btn">{{text}}</buttton>
</template>

<script>
export default {
name:'Button',
props:{
    text:String,
    color:String
},
methods:{
    onClick(){
        console.log('click')
    }



    
}
}
</script>

<style>

</style>