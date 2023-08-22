<template>
  <div class="dashboard-layout">
    <div class="dashboard-inner-layout">
      <sidebar></sidebar>
      <mainContent></mainContent>
      <bookingList></bookingList>
    </div>
  </div>
</template>

<script>
import SidebarComponent from './SidebarComponent.vue';
import mainContent from './mainContent.vue';
import bookingList from './bookingList.vue';

export default {
  components: {
    Sidebar: SidebarComponent,
    mainContent,
    bookingList,
  },
};
</script>

<style>
.dashboard-layout {
  display: flex;
  justify-content: center;
  background: #b6d0e2;
  margin: 20px;
  padding: 100px;
}
.dashboard-inner-layout {
  display: flex;
  background: linear-gradient(135deg, #f7f7f7 70%, #ffccff);
  border-radius: 50px;
  border: 10px solid black;
}
</style>
