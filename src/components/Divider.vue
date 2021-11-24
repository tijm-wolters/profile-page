<template>
  <div class="seperator">{{ text }}</div>
</template>

<script>
export default {
  name: 'Divider',
  props: ['text'],
};
</script>

<style lang="scss" scoped>
.seperator {
  display: flex;
  align-items: center;
  text-align: center;

  &::before,
  &::after {
    content: '';
    flex: 1;
    border-bottom: 1px solid $accent-color;
  }
  &::before {
    margin-right: 0.5em;
  }
  &::after {
    margin-left: 0.5em;
  }
}
</style>
