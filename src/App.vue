<template>
  <div id="app">
    <div class="ratio ratio-375x281">
      <img
        class="img-fluid shadow"
        src="./assets/images/back.jpg"
        alt="Header"
      />
    </div>
    <div class="text-center">
      <img
        width="334"
        height="170"
        src="./assets/images/temno.png"
        alt="Logo"
      />
    </div>
    <router-view />
    <footer class="py-2 text-center">Изработено од Давид Митков и Бојан Поповски</footer>
  </div>
</template>

<style lang="scss"></style>
