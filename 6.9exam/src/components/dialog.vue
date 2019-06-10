<template>
    <div class="mask">
        <div class="content">
            <header>{{head}}</header>
            <div class="cont">{{diacont}}</div>
            <button v-for="(item,index) in btn" :key="index">{{item}}</button>
        </div>
    </div>
</template>
<script>
export default {
    props:['head',"diacont",'btn'],
    components:{

    },
    data(){
        return {

        }
    },
    computed:{

    },
    methods:{

    },
    created(){

    },
    mounted(){

    }
}
</script>
<style scoped lang="">

</style>