<template>
  <footer class="copyright">
    &copy; {{ currentYear }} xmHo9 Co., Ltd. All rights reserved.
  </footer>
</template>

<script>
export default {
  name: 'Copyright',
  data() {
    return {
      currentYear: new Date().getFullYear()
    };
  }
};
</script>

<style scoped>
.copyright {
  text-align: center;
  padding: 20px;
  background-color: #f8f9fa;
  color: #6c757d;
  font-size: 14px;
}
</style>
