<template>
<div class='test'>
    <input :value='val' @input='val=$event.target.value'>
    <span>{{val}}</span>
</div>
    
</template>
<script>
export default {
  data(){
      return{
          val:'sadas'
      }
  },
  methods:{
    change(e){
      console.log(e)
    }
  }
    
}
</script>
<style scoped lang="stylus">
  .test
    input 
      width:30rem
      height 3rem
      background:#d1d1d1
      font-size:2rem
    span 
      color:#afa
      font-size:3rem
      display:block
</style>


