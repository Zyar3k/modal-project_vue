<template>
  <div class="backdrop">
    <div class="modal">
      <h1>Modal title</h1>
      <p>modal content</p>
    </div>
  </div>
</template>

<!-- <style scoped> -->
<style>
.modal {
  width: 400px;
  padding: 20px;
  margin: 100px auto;
  background: #fff;
  border-radius: 10px;
}
.backdrop {
  top: 0;
  position: fixed;
  background: rgba(0, 0, 0, 0.5);
  width: 100%;
  height: 100%;
}
.modal h1 {
  color: #03cfb4;
  padding: 0;
  border: none;
}
.modal p {
  font-style: normal;
}
</style>