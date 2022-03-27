<script>
import ChildSlot from '../components/ChildSlot.vue'

export default {
  components: {
    ChildSlot
  },
  data() {
    return {
      msg: '爸爸在这里'
    }
  }
}
</script>

<template>
  <ChildSlot>父组件传递的值：{{msg}}</ChildSlot>
<p></p>
<ChildSlot></ChildSlot>
</template>