<template>
  <div class="wrapper">
    <header>
      <a href="#">
        <img
          class="vector-primary"
          src="https://i.imgur.com/PYbiwrX.png"
          alt=""
        />
      </a>
      <div class="title">
        <h5>John Doe</h5>
        <p>29 推文</p>
      </div>
    </header>
    <div class="profile">
      <img class="cover-image" src="https://i.imgur.com/H3ADasp.png" alt="" />
      <img class="avatar" src="https://i.imgur.com/sFuDF3M.png" alt=""  />
      <a href="#">
        <button class="btn-edit">編輯個人資料</button>
      </a>
      <div class="info">
        <div class="names">
          <h5 class="user-name">John Doe</h5>
          <p class="user-account">@John Doe</p>
        </div>
        <p class="description">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        </p>
        <div class="follow-ship">
          <a class="following" href="#">34個<span>追隨中</span></a>
          <a class="follower" href="#">59位<span>追隨者</span></a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
};
</script>

<style scoped>
.wrapper {
  margin-bottom: 31px;
}
header {
  height: 74px;
  width: 100%;
  display: flex;
  flex-flow: row nowrap;
  align-items: center;
}
.vector-primary {
  width: 17px;
  height: 14px;
  margin: auto 28px auto 19px;
}
.title p {
  font-size: 13px;
  font-weight: 500;
  color: #6c757d;
}
.profile {
  position: relative;
}
.cover-image {
  display: block;
  width: 100%;
  height: 200px;
  object-fit: cover;
}
.avatar {
  display: block;
  width: 140px;
  height: 140px;
  position: absolute;
  left: 16px;
  top: 124px;
}
.btn-edit {
  position: absolute;
  top: 216px;
  right: 16px;
  background: #ffffff;
  border: 1px solid #ff6600;
  border-radius: 50px;
  font-size: 16px;
  line-height: 24px;
  font-weight: 400;
  color: #ff6600;
  width: 128px;
  height: 40px;
}
.info {
  margin-top: 72px;
  margin-left: 16px;
  font-size: 14px;
  line-height: 22px;
}
.info .user-account,
.follow-ship > a > span {
  color: #6c757d;
}
.description,
.follow-ship a {
  text-decoration: none;
  color: #171725;
}
.description {
  margin-top: 6px;
  margin-bottom: 8px;
}
.following {
  margin-right: 20px;
}
</style>