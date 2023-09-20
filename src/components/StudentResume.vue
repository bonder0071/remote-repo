<template>
  <div class="student-resume">
    <div class="header">
      <img class="avatar" src="@/assets/avatar.jpg" alt="Avatar" />
      <h1>{{ studentName }}</h1>
      <p>{{ studentNickname }}</p>
      <p>{{ studentID }}</p>
    </div>
    <h2>教育背景</h2>
    <ul>
      <li>{{ education }}</li>
    </ul>
    <h2>工作经验</h2>
    <ul>
      <li>{{ experience }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      studentName: 'Lsy',
      studentNickname: 'Bonder007',
      studentID: '42354324',
      education: '辽宁工程技术大学- University of Example, 2023',
      experience: '华为实习 (2020 - Present)',
    };
  },
};
</script>

<style scoped>
/* 样式可以根据需要自行添加 */
.header {
  text-align: center;
}

.avatar {
  width: 150px; /* 调整头像尺寸 */
  height: 150px;
  border-radius: 50%; /* 圆形头像 */
  margin: 10px auto;
  display: block;
}
</style>
