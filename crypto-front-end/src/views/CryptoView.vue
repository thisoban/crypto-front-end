<template>
  <div class="about">
    <h1>This is an crypto page</h1>

    <div class="cryptolistings">
      <table>
        <tr>
            <th>ranking number </th>
            <th>name </th>
            <th> price </th>
            <th>24% </th>
            <th>7d% </th>
            <th>market cap </th>
            <th>volume(24h) </th>
            <th>circulating supply </th>
        </tr>
        
      </table>
    </div>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
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