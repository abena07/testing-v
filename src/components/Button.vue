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
      this.$emit('toggle-add-task')
    }



    
}
}
</script>

<style>

</style>