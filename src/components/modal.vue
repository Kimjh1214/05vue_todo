<template>
  <div class="modalContainer">
      <div>
          <slot name="header"></slot>
      </div>
      <div>
          <slot name="footer"></slot>
      </div>
  </div>
</template>

<script>
export default {
    name:'modalContainer',
}
</script>

<style>
    .modalContainer{
        background: pink;
        position: fixed;
        width: 300px;
        padding: 20px 30px;
        left: 50%; top: 50%;
        transform:translate(-50%,-50%);
    }
</style>