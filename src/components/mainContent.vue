<template>
  <div class="main-content">
    <div class="search-bar">
      <i class="search-icon fa fa-search"></i>
      <input type="text" class="search-input" placeholder="Search" />
    </div>
    <div class="line"></div>
    <div>
      <div>
        <h1 style="font-size: xxx-large; display: flex">
          <span style="color: lightgray; font-size: xxx-large">Welcome, </span
          >William
        </h1>
        <span style="display: flex"
          ><h5>You have <u>9 free rooms</u> at Saint Denis</h5></span
        >
      </div>

      <img src="../../static/images/grids.jpg" />
    </div>
    <div>
      <img src="../../static/images/chart.jpg" />
    </div>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'mainContent',
};
</script>

<style scoped>
.main-content {
  flex: 1;
  padding: 20px;
}
.search-bar {
  display: flex;
  align-items: center;
  padding: 8px;
  margin-bottom: 20px;
  margin-top: 20px;
}

.search-icon {
  margin-right: 30px;
  color: black;
  font-size: large;
}

.search-input {
  border: none;
  outline: none;
  width: 100%;
  background: transparent;
  font-size: 20px;
}

.line {
  flex: 1;
  border-top: 1px solid #ccc;
  margin-bottom: 10px;
}
</style>
