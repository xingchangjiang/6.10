<template>
  <div class="wrap">
    <button @click=add>点击</button>
    <Dialog
    v-show="flag"
    :head="head"
    :diacont="diacont"
    :btn="btn"
    ></Dialog>
  </div>
</template>
<script>
import Dialog from './components/dialog'
export default {
  props:{

  },
  components:{
    Dialog
  },
  data(){
    return {
      head:'弹框+2',
      diacont:'内容+2',
      btn:["确定","取消","不知道"],
      flag:false
    }
  },
  computed:{

  },
  methods:{
    add(){
      this.flag=!this.flag
    }
  },
  created(){

  },
  mounted(){

  }
}
</script>
<style scoped lang="">

</style>