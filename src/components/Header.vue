<template>
  <div class="header">
    <div class="image">
      <img src="../assets/400px-tijm-wolters.png" alt="Tijm Wolters" />
    </div>
    <div class="text">
      <h1><span class="first-name">Tijm</span> Wolters</h1>
      <h2>Software Engineer</h2>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
};
</script>

<style lang="scss" scoped>
.header {
  align-items: center;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  gap: 32px;
  margin: 64px;
  justify-content: center;

  .text {
    white-space: nowrap;
  }

  .first-name {
    color: $accent-color;
  }

  img {
    border-radius: 100%;
    box-shadow: 0 0 10px $accent-color;
    max-height: 200px;
    max-width: 200px;
  }

  h2 {
    font-weight: 200;
    font-size: 1.4rem;
  }

  h1,
  h2 {
    margin: 0;
  }
}
</style>
