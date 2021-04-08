<template>
  <div class="header flex">
    <div class="left">
      <img src="../assets/logo.png" alt="#" class="logo">
    </div>
    <div class="right flex">
      <p @click="$route.push('/signup')">新規登録</p>
      <p @click="$route.push('/')">ログイン</p>
    </div>
  </div>
</template>

<style scoped>
.right {
 align-items: center;
}
.right p {
 margin-right: 20px;
 cursor: pointer;
}
.header {
 margin: 20px;
}
.logo {
 width: 150px;
 cursor: pointer;
}
.flex {
 display: flex;
 justify-content: space-between;
}
</style>