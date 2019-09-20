<template>
  <div class="body">
    <a-button @click="showConfirm">
      Confirm
    </a-button>
  </div>
</template>

<script>
export default {
  name: 'Index',
  data() {
    return {
      visible: false,
    };
  },
  mounted() {

  },
  methods: {
    confirm() {
      this.$message.success('Click on Yes');
    },
    cancel() {
      this.$message.error('Click on No');
    },
    showDrawer() {
      this.visible = true;
    },
    onClose() {
      this.visible = false;
    },
    showConfirm() {
      this.$confirm({
        title: 'Do you want to delete these items?',
        content: 'When clicked the OK button, this dialog will be closed after 1 second',
        onOk() {
          return new Promise((resolve, reject) => {
            setTimeout(Math.random() > 0.5 ? resolve : reject, 1000);
          }).catch(() => console.log('Oops errors!'));
        },
        onCancel() {},
      });
    },
  },
};
</script>

<style lang="less">
.body {
  margin: 10px;
}
</style>