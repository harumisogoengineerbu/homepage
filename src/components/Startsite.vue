<template>
  <div class="section section-startsite">
    <div class="main-section">
      <div class="left-column">
        <h1>O MO TE NA SHI</h1>
        <p>
          Omotenashi is to welcome guests with a heart that doesn't change
          depending on something
        </p>
        <table>
          <tr>
            <th>our contents</th>
          </tr>
          <tr>
            <td>
              <a href="#foods">Japnese Foods</a>
            </td>
          </tr>
          <tr>
            <td>
              <a href="#cultures">Japanese Cultures</a>
            </td>
          </tr>
        </table>
      </div>
      <div class="right-column">
        <img src="../assets/kyoto-night.jpg" height="400" />
      </div>
    </div>
  </div>
</template>

<style>
@import "../css/main.css";

.section-startsite .left-column {
  width: 50%;
  padding-right: 30px;
}

.section-startsite .left-column p {
  font-size: 1.75rem;
  margin-top: 30px;
  line-height: 70px;
}

.section-startsite .left-column table {
  margin: 0 auto;
}

.section-startsite .left-column table th {
  font-size: 2rem;
  background-color: #2c3e50;
  color: #fff;
}

.section-startsite .left-column table td {
  font-size: 1.75rem;
  padding-top: 10px;
}

.section-startsite .left-column table td a {
  color: #2c3e50;
  text-decoration: none;
}

.section-startsite .right-column {
  width: 50%;
}

.section-startsite .right-column img {
  width: 100%;
}
</style>