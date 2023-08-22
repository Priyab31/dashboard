<template>
  <div class="sidebar">
    <div style="margin-bottom: 100px; display: flex; align-items: center">
      <i
        class="fa fa-cutlery"
        aria-hidden="true"
        style="font-size: xxx-large"
      ></i>
      <h2 style="margin-left: 10px">
        HOTEL<span style="color: lightgrey"> SWAN</span>
      </h2>
    </div>
    <div class="menu">
      <div class="menu-item" style="color: blue; background: #ededed">
        <div class="icondiv"><i class="fa-solid fa-chart-line"></i></div>
        Overview
      </div>
      <div class="menu-item">
        <div class="icondiv">
          <i class="fa-regular fa-calendar-days"></i>
        </div>
        Calendar
      </div>
      <div class="menu-item">
        <div class="icondiv"><i class="fa-solid fa-key"></i></div>
        Booking
      </div>
      <div class="menu-item">
        <div class="icondiv">
          <i class="fa-regular fa-credit-card"></i>
        </div>
        Earnings
      </div>
      <div class="menu-item">
        <div class="icondiv"><i class="fa-solid fa-user-group"></i></div>
        Stuff
      </div>
    </div>

    <div class="icon-circle">
      <i class="fa fa-comment" aria-hidden="true"></i>
    </div>

    <div class="icon-oval">
      <div class="settings">
        <i class="settings-icon fa fa-cog"></i>
        Settings
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SidebarComponent',
};
</script>

<style scoped>
.sidebar {
  width: 250px;
  background-color: white;
  color: #555;
  padding: 20px;
  margin: 20px;
  border-radius: 30px;
}

.menu {
  list-style: none;
  padding: 0;
}

.menu-item {
  display: flex;
  align-items: center;
  padding: 10px;
  text-decoration: none;
  color: #555;
  transition: background-color 0.3s;
  cursor: pointer;
  border-radius: 10px;
}

.menu-item:hover {
  background-color: #ededed;
}

.icondiv {
  margin-right: 30px;
}

.icon-circle {
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #f8c8dc;
  width: 40px;
  height: 40px;
  border-radius: 50%;
  position: absolute;
  margin-top: 400px;
  margin-right: 20px;
  margin-left: 40px;
}
.icon-oval {
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #ededed;
  width: 120px;
  height: 50px;
  border-radius: 50%;
  margin-top: auto;
  position: absolute;
  margin-top: 400px;
  margin-right: 20px;
  margin-left: 100px;
}

.settings {
  display: flex;
  align-items: center;
  color: black;
}
.settings-icon {
  font-size: 20px;
  margin-right: 8px;
}
</style>
