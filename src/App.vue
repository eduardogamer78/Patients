<template>
  <q-layout view="lHh Lpr lFf">
    <SideBar />
    <RightSidebar />
    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>

import RightSidebar from "@/components/RightSidebar";
import SideBar from "@/components/SideBar";
export default {
  name: 'LayoutDefault',

  components: {
    SideBar,
    RightSidebar,
  },

  setup () {
    return {

    }
  }
}
</script>
