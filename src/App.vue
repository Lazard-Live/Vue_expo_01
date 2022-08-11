<template>
  <div class="wrapper">
    <img
      alt="Vue logo"
      class="logo"
      src="src/assets/logo.svg"
      width="50"
      height="50"
    />

    <div>
      <input type="text" />
      <button>Добавить</button>
      <div class="list"></div>
    </div>
  </div>
</template>

<style scoped lang="scss">
.wrapper {
  display: flex;
  flex-direction: column;
  align-items: center;
}
</style>
