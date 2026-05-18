<template>
  <main class="main-light">
      <router-View />
  </main>
</template>

<style scope>

  main {
    overflow: hidden;
    width: 100%;
    height: 100%;
  }

  .main-light {
    background-color: var(--background-light);
  }

  .component {
    background-color: var(--component-background-light);
  }

  body {
        width: 100%;
        height: 100%;
    }

  html {
    width: 100%;
    height: 100%;
  }
</style>
