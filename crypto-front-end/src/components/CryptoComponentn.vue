<script> 
import crypto from "../temp/crypto.json"

  export default{
  name: "crypto",
  data: () => {
    return {
      isHidden: false,
      data: crypto
    }
  },
  created() {
    console.log(this.data);
  }
}

</script>ghn
<template >
  <!-- {{data}}  -->
  <tr v-for="(item, index) in data.data" :key="item.id">
    <td><b>{{index + 1}}</b></td>
    <td>{{item.id}}</td>  
    <td>{{item.name}}</td> 
    <td>{{item.symbol}}</td>
  </tr>
</template>
<style scoped>

</style>