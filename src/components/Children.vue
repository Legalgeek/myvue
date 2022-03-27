<script>
export default {
    emits: ["childreninfo"],
    props: {
        msgChild: String
    }, created() {
        this.$emit("childreninfo", "这是子组件提交的信息，将由父组件渲染：love from child")
    }
}


</script>

<template>
    <h2>{{ msgChild || 'No props passed yet' }}</h2>
</template>
