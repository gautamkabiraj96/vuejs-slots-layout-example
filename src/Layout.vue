<template>
  <div>
    <header class="header-slot">
      <slot name="header"></slot>
    </header>
    <main class="main-slot">
      <slot></slot>
    </main>
    <footer class="footer-slot">
      <slot name="footer"></slot>
      <div class="np-credits">wwww.nightprogrammer.com</div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "Layout",
};
</script>

<style scoped>
.header-slot {
  background: #eee;
  padding: 10px 6px;
}
.main-slot {
  padding: 16px 6px;
}
.footer-slot {
  background: #eee;
  padding: 10px 6px;
}
</style>