<template>
  <div>
    <fa class="icon" :icon="['fas', 'search']" />
    <fa class="icon" :icon="['fas', 'user']" />
    <fa class="icon" :icon="['fas', 'bars']" />
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
div {
  display: flex;
  align-items: center;
  justify-content: flex-end;
  width: 100%;
  height: 40px;
  border-bottom: 1px solid #e7e7e7;
  > .icon {
    margin-left: 50px;
    margin-right: 20px;
  }
}
</style>