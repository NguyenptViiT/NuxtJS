<template>
  <div class="">
    <Header />
    <div
      class="flex flex-row gap-x-[32px] pt-[26px] shadow pb-[30px] px-[11px]"
    >
      <div class="basis-[75%]">1</div>
      <div class="basis-[25%] pt-[4px]">
        <FollowUs />
        <Blogging />
        <Advertising />
        <Fashion />
      </div>
    </div>
  </div>
</template>

<script setup>
import Header from "../layouts/Header";
// import FollowUs from "../components/FollowUs";
// import Blogging from "../components/Blogging";
// import Advertising from "../components/Advertising";
</script>

<style lang="scss" scoped></style>
