<template>
  <div class="flex between mb-15">
    <input type="text" class="input-update">
    <div>
      <button class="button-update">更新</button>
      <button class="button-delete">削除</button>
    </div>
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
.input-update{
  width: 30%;
  padding: 5px;
  border-radius: 5px;
  border: 1px solid #ccc;
  appearance: none;
  font-size: 14px;
  outline: none;
}
.button-update{
  text-align: left;
  border: 2px solid #fa9770;
  font-size: 12px;
  color: #fa9770;
  background-color: #fff;
  font-weight: bold;
  padding: 8px 16px;
  border-radius: 5px;
  cursor: pointer;
  transition: 0.4s;
  outline: none;
}
.button-delete{
  text-align: left;
  border: 2px solid #71fadc;
  font-size: 12px;
  color: #71fadc;
  background-color: #fff;
  font-weight: bold;
  padding: 8px 16px;
  border-radius: 5px;
  cursor: pointer;
  transition: 0.4s;
  outline: none;
}
</style>