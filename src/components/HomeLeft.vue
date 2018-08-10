<template>
  <div class="head-left">
    <div class="avatar-wrap">
      <div class="avatar">
        <img src="https://blog.dbdl.cc/wp-content/uploads/2017/12/头像.png">
      </div>
      <h1 class="panel-title">
        <a href="https://blog.dbdl.cc">云雾迷蒙</a>
      </h1>
      <span>生活总让人措手不及</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeLeft',
  data () {
    return {

    }
  }
}
</script>

<style lang="less" scoped>
.head-left {
  position: fixed;
  top: 80px;
  width: 187px;
  background: #ffffff;
  text-align: center;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 0 0 1px rgba(0, 0, 0, 0.02), 0 4px 10px rgba(0, 0, 0, 0.06);
}
.avatar-wrap {
  .avatar {
    padding: 28px 28px 10px;
    text-align: center;
    img {
      max-width: 100px;
      border-radius: 100%;
      border: 1px solid #eee;
      transition: all 0.2s ease-in;
    }
  }
  .panel-title {
    color: rgba(0,0,0,.8);
    font-size: 20px;
  }
}
</style>
