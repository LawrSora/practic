<template>
  <main class="main-light">
      <router-View />
      <div class="component">H</div>
  </main>
</template>

<style scope>

  main {
    overflow: hidden;
    width: 100%;
    height: 100vh;
  }

  .main-light {
    background-color: var(--background-light);
  }

  .component {
    background-color: var(--component-background-light);
  }
</style>
