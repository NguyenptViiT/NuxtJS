<template>
  <header>
    <div class="header-icon p-[11px] flex justify-between">
      <ul class="flex gap-x-[18px] text-white text-[12px]">
        <li>
          <NuxtLink to="#">About</NuxtLink>
        </li>
        <li>
          <NuxtLink to="#">Contact</NuxtLink>
        </li>
        <li class="relative fullWidthPage">
          <div class="flex gap-x-[2px] items-center">
            <NuxtLink to="#">Full Width Page</NuxtLink>
            <ArrowBottom colorprops="white" />
          </div>
          <div class="fullWidthPage-hover">
            <div
              class="absolute bottom-[-60%] translate-y-[100%] left-0 text-black w-[200%] bg-white shadow p-[8px] flex flex-col gap-y-[10px]"
            >
              <span class="border-b pb-[10px]">
                <NuxtLink to="#">Sub menu 1</NuxtLink>
              </span>
              <span class="border-b pb-[10px]">
                <NuxtLink to="#">Sub menu 2</NuxtLink>
              </span>
              <span class="">
                <NuxtLink to="#">Sub menu 3</NuxtLink>
              </span>
            </div>
          </div>
        </li>
        <li>
          <NuxtLink to="#">Submit Article</NuxtLink>
        </li>
        <li>
          <NuxtLink to="#">Buy Theme</NuxtLink>
        </li>
      </ul>
      <div class="flex gap-x-[12px]">
        <DribbbleIcon />
        <FacebookIcon />
        <InstagramIcon />
        <LinkedinIcon />
        <TwitterIcon />
        <YoutubeIcon />
      </div>
    </div>
  </header>
</template>

<script setup>
import ArrowBottom from "../../components/svgs/ArrowBottom.vue";
import DribbbleIcon from "../../components/svgs/DribbbleIcon.vue";
import FacebookIcon from "../../components/svgs/FacebookIcon.vue";
import InstagramIcon from "../../components/svgs/InstagramIcon.vue";
import LinkedinIcon from "../../components/svgs/LinkedinIcon.vue";
import TwitterIcon from "../../components/svgs/TwitterIcon.vue";
import YoutubeIcon from "../../components/svgs/YoutubeIcon.vue";
</script>

<style lang="scss" scoped></style>
