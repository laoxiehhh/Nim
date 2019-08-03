<template>
  <div class="wrapper">
    <div class="section">
      <label for="name1">姓名1：</label>
      <input type="text" v-model="name1" id="name1" />
    </div>
    <div class="section">
      <label for="name2">姓名2：</label>
      <input type="text" v-model="name2" id="name2" />
    </div>
    <div class="section">
      <label for="name3">姓名3：</label>
      <input type="text" v-model="name3" id="name3" />
    </div>
    <div class="section">
      <label for="name4">姓名4：</label>
      <input type="text" v-model="name4" id="name4" />
    </div>
    <div class="section">
      <label for="name5">姓名5：</label>
      <input type="text" v-model="name5" id="name5" />
    </div>
    <div class="section">
      <label for="name6">姓名6：</label>
      <input type="text" v-model="name6" id="name6" />
    </div>
    <div class="section">
      <button v-on:click="handleClick">提交</button>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name1: "",
      name2: "",
      name3: "",
      name4: "",
      name5: "",
      name6: ""
    };
  },
  methods: {
    handleClick() {
      const name1 = this.name1;
      console.log(name1);
    }
  }
};
</script>


<style>
.wrapper {
  display: flex;
  align-items: center;
  justify-items: center;
  flex-direction: column;
}
.section {
  height: 60px;
  width: 300px;
}
</style>
