<script setup>
import { RouterLink, RouterView } from "vue-router";

function mobileMenuToggle() {
  let mobileNav = document.getElementsByClassName("mobileNav");
  if (mobileNav[0].style.display === "") {
    mobileNav[0].style.display = "block";
  } else {
    mobileNav[0].style.display = "";
  }
}
</script>

<template>
  <header class="fixed w-full">
    <div class="container">
      <div class="xl:px-auto flex items-center justify-between py-6 px-1">
        <h1 class="h-6p5 w-61 xl:h-8 xl:w-79">
          <RouterLink
            to="/"
            class="block h-full w-full bg-logo bg-contain bg-center xl:bg-cover"
          ></RouterLink>
        </h1>
        <button class="nav_menu_btn" @click="mobileMenuToggle()">
          <div class="h-10 w-10 bg-icon-menu xl:hidden"></div>
        </button>
        <nav class="-mx-5 hidden items-center xl:flex">
          <RouterLink to="/about" class="mx-5 block text-xl"
            >登入/註冊</RouterLink
          >
          <RouterLink
            to="/about"
            class="mx-5 block rounded-md bg-primary py-4 px-8 text-xl text-white"
            >訂閱方案</RouterLink
          >
        </nav>
      </div>
    </div>
    <nav class="mobileNav fixed top-0 z-10 hidden w-full bg-white p-10">
      <div class="mb-3 flex w-full flex-row-reverse">
        <button class="cancel_btn" @click="mobileMenuToggle()">
          <div class="h-10 w-10 bg-icon-cancel xl:hidden"></div>
        </button>
      </div>
      <div>
        <div class="mb-6 h-6p5 w-61 xl:h-8 xl:w-79">
          <RouterLink
            to="/"
            class="block h-full w-full bg-logo bg-contain bg-center xl:bg-cover"
          ></RouterLink>
        </div>
        <div class="mb-6">
          <RouterLink to="/about" class="text-xl">登入/註冊</RouterLink>
        </div>
        <div class="flex h-13 items-center">
          <RouterLink
            to="/about"
            class="rounded-md bg-primary py-2 px-4 text-xl text-white"
            >訂閱方案</RouterLink
          >
        </div>
      </div>
    </nav>
  </header>
  <RouterView />
  <footer class="bg-primary">
    <div class="container pb-15 pt-10 xl:pb-13">
      <div
        class="mb-10 h-7 w-68 bg-logo-footer bg-cover bg-center xl:mb-6"
      ></div>
      <div
        class="border-b-2 border-white pb-10 xl:flex xl:items-center xl:justify-between xl:pb-6"
      >
        <div class="mb-10 flex gap-3 xl:mb-0">
          <RouterLink to="#" class="h-13 w-13">
            <div class="h-full w-full bg-icon-line bg-cover bg-center"></div>
          </RouterLink>
          <RouterLink to="#" class="h-13 w-13">
            <div class="h-full w-full bg-icon-ig bg-cover bg-center"></div>
          </RouterLink>
          <RouterLink to="#" class="h-13 w-13">
            <div class="h-full w-full bg-icon-fb bg-cover bg-center"></div>
          </RouterLink>
        </div>
        <div class="flex flex-col items-start xl:flex-row">
          <div class="mr-5 flex items-center">
            <div class="mb-2 mr-1 h-10 w-10 xl:mb-0">
              <div class="h-full w-full bg-icon-mail bg-cover bg-center"></div>
            </div>
            <span class="text-xl font-medium text-white">聯絡我們</span>
          </div>
          <div>
            <p class="mb-2 text-xl font-medium text-white xl:mb-4">
              Service@ideaHako.com.tw
            </p>
            <span class="text-xl font-medium text-white">0800-000-000</span>
          </div>
        </div>
      </div>
      <div class="flex flex-col justify-between pt-3 xl:flex-row">
        <p class="mb-3 font-medium text-white xl:mb-0">
          © IdeaHako 2022 All rights reserved.
        </p>
        <div class="flex gap-2">
          <RouterLink to="#" class="text-white">服務條款</RouterLink>
          <span class="text-white">|</span>
          <RouterLink to="#" class="text-white">隱私權條款</RouterLink>
        </div>
      </div>
    </div>
  </footer>
</template>

<style scoped></style>
