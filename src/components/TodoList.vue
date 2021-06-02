<template>
  <div class="flex between mb-15">
    <input type="text" class="input-add" v-model="message" />
    <button class="button-add">追加</button>
  </div>
</template>

<style scoped>
.mb-15{
  margin-bottom: 15px;
}
.between{
  justify-content: space-between;
}
.flex{
  display: flex;
}
.input-add{
  width: 80%;
  padding: 5px;
  border-radius: 5px;
  border: 1px solid #ccc;
  appearance: none;
  font-size: 14px;
  outline: none;
}
.button-add{
  text-align: left;
  border: 2px solid #dc70fa;
  font-size: 12px;
  color: #dc70fa;
  background-color: #fff;
  font-weight: bold;
  padding: 8px 16px;
  border-radius: 5px;
  cursor: pointer;
  transition: 0.4s;
  outline: none;
}
</style>