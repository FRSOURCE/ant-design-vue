<docs>
---
order: 3
title:
  zh-CN: 多色图标
  en-US: Two-tone icon and colorful icon
---

## zh-CN

双色图标可以通过 `two-tone-color` 属性设置主题色。

## en-US

You can set `two-tone-color` prop to specific primary color for two-tone icons.

</docs>

<template>
  <div class="icons-list">
    <smile-two-tone />
    <heart-two-tone two-tone-color="#eb2f96" />
    <check-circle-two-tone two-tone-color="#52c41a" />
  </div>
</template>
<script>
import { SmileTwoTone, HeartTwoTone, CheckCircleTwoTone } from '@ant-design/icons-vue';
export default {
  components: {
    SmileTwoTone,
    HeartTwoTone,
    CheckCircleTwoTone,
  },
};
</script>
<style scoped>
.icons-list :deep(.anticon) {
  margin-right: 6px;
  font-size: 24px;
}
</style>
