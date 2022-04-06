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
        <tr>
          <th scope="row">1</th>
          <td>Mark</td>
          <td>Otto</td>
          <td>@mdo</td>
        </tr>
        <tr>
          <th scope="row">2</th>
          <td>Jacob</td>
          <td>Thornton</td>
          <td>@fat</td>
        </tr>
        <tr>
          <th scope="row">3</th>
          <td>Larry</td>
          <td>the Bird</td>
          <td>@twitter</td>
        </tr>
       <CryptoComponentnVue></CryptoComponentnVue>
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