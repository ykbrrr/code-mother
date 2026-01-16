<template>
  <a-layout-footer class="global-footer">
    <div class="footer-content">
      <p>项目作者：叶凯</p>
    </div>
  </a-layout-footer>
</template>

<script setup lang="ts">
// 页脚组件，固定在底部
</script>

<style scoped>
.global-footer {
  text-align: center;
  background: #f0f2f5;
  padding: 16px 24px;
  position: relative;
  margin-top: auto;
}

.footer-content {
  color: rgba(0, 0, 0, 0.65);
  font-size: 14px;
}

/* 响应式设计 */
@media (max-width: 768px) {
  .global-footer {
    padding: 12px 16px;
  }

  .footer-content {
    font-size: 12px;
  }
}
</style>
