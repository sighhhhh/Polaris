

<template>
  <div :id="dynamicID" :class="dynamicClass"> {{ title }} </div>
  <p>{{ welecome }}</p>
  <textarea class="box_25">Input Here !</textarea><br>
  <button :disabled="isBtnDisabled" class="button-29" role="button">Click Here !</button><br>
  <button :disabled="isBtnDisabled" class="button-85" role="button">Click Here !</button><br>
  <button :disabled="isBtnDisabled" class="button-86" role="button">Click Here !</button><br>
</template>

<script>

export default {
  data() {
    return {
      title: "Polaris",
      welecome: "Hello! Welecome to Polaris !",
      dynamicID: "AppID",
      dynamicClass: "AppClass",
      isBtnDisabled: false
    }
  }
}
</script>

<style>
.AppClass {
  color: rgb(59, 47, 122);
  font-size: 50px;
}
</style>