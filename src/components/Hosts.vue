<template>
  <div>
    <h3>Hosted by</h3>
    <ul class="hosts">
      <li>
        <a href="https://twitter.com/A_Deduchovas" target="_blank"><img src="../assets/kJ5-Kwma_400x400.jpg" alt="Antonas Deduchovas" />Antonas</a>
      </li>
      <li>
        <a href="https://twitter.com/NikkitaFTW" target="_blank"><img src="../assets/GRGg5x8v_400x400.jpg" alt="Sara Vieira" />Sara</a>
      </li>
    </ul>
  </div>
</template>
<style scoped lang="scss">
.hosts {
  display: flex;
  align-items: center;
  list-style: none;
  justify-content: center;

  li {
    margin: 0 5px;
    font-weight: bold;

    a {
      display: flex;
      align-items: center;
      flex-direction: column;
    }

    img {
      width: 120px;
      margin-bottom: 10px;
      transition: all 200ms ease-in;
      box-shadow: none;
      border: 1px solid #e7e85a;

      &:hover {
        box-shadow: 1px 2px 5px rgba(0, 0, 0, 0.4);
      }
    }
  }
}
</style>
