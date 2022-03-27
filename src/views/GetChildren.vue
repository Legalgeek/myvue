<script>
import ChildrenVue from "../components/Children.vue";

export default{
    data(){
        return{
            msgChild:"这是从父组件发出的信息，将由子组件渲染",
            msg:"not yet"
        }
    },
    components:{
        ChildrenVue
    }
}

</script>


<template>
<ChildrenVue :msgChild="msgChild" @childreninfo="(info) => msg = info"/>
<p>{{msg}}</p>
</template>