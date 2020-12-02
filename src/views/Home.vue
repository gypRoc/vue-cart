<template>
  <div class="home">
    <app-bar title="INTEREST" left="search" right="crosshairs" />
    <tab-list></tab-list>
    <card-list />
    <card-detail></card-detail>
  </div>
</template>

<script>
import AppBar from '@/components/AppBar.vue'
import TabList from '@/components/TabList.vue'
import CardList from '@/components/CardList.vue'
import CardDetail from '@/components/CardDetail.vue'
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  // name: 'Home',
  components: {
    AppBar,
    TabList,
    CardList,
    CardDetail
  }
}
</script>

<style lang="scss">
.home {
  height: 100%;
  width: 100%;
  overflow: hidden;
  color: white;
  background-image: linear-gradient(to top, #99acbe 5%, #a8b3bf 20%, #cfd7dd);
}
</style>
