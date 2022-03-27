<script>
export default {
  data(){
    return{
      msg:"hello minglei"
    }
  }
  // component options
}
</script>

<template>
  <h1>{{msg.split("").reverse().join("")}}</h1>
</template>

<style>
/* h1 {
  text-align: center;
  cursor: pointer;
  margin-top: 3em;
} */
</style>