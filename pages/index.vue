<template>
  <div class="">
    <Header />
    <div class="flex flex-row gap-x-[32px] pt-[26px] shadow pb-[30px]">
      <div class="basis-[75%]">1</div>
      <div class="basis-[25%]">
        <FollowUs />
      </div>
    </div>
  </div>
</template>

<script setup>
// import TwitterIcon from "../components/svgs/TwitterIcon.vue";
import Header from "../layouts/Header";
import FollowUs from "../components/FollowUs";
</script>

<style lang="scss" scoped></style>
