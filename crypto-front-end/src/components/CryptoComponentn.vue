<script> 
import crypto from "../temp/crypto.json"

export default{
 name: "crypto",
  data: () => {
    return {
      isHidden: false,
      data: crypto
    }
  }
}

</script>
<template>
{{data}}
  <tr v-for="(item,index) in data" :key="item.id">
       <th scope="row">2</th>
          <td>{{item[index]}}</td>
          <td>Thornton</td>
          <td>@fat</td>
  </tr>
</template>
<style scoped>

</style>