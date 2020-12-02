<template>
  <!-- 直接使用类名引入 -->
  <i :class="'el-icon-' + name"></i>
</template>

<script>
  export default {
    name: 'ElIcon',

    props: {
      name: String
    }
  };
</script>
