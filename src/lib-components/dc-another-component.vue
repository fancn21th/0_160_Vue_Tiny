<template>
  <alert message="Success Text" type="success" />
</template>

<script>
import Alert from "ant-design-vue/lib/alert";
// TODO: 按需加载
import "ant-design-vue/dist/antd.css";

export default {
  components: {
    Alert,
  },
};
</script>

<style></style>
