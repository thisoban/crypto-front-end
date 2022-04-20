<script>
import CryptoComponentnVue from "../components/CryptoComponentn.vue"
export default {
  components: {
    CryptoComponentnVue
  }
}
</script>

<template>
    <div class="cryptolistings">
      <table class="table">
        <thead>
          <tr>
            <th scope="col">#</th>
            <th scope="col">First</th>
            <th scope="col">Last</th>
            <th scope="col">Handle</th>
          </tr>
        </thead>
      <tbody>
       <CryptoComponentnVue/>
      </tbody>
    </table>
    </div>
</template>

<style>
table{
  width: 100%;
}

tr, th {
  border: 1px solid white;
  text-align: left;
  padding: 8px;
}
</style>
9 