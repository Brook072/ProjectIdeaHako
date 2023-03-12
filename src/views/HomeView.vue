<script setup>
import { RouterLink } from "vue-router";
</script>

<template>
  <main>
    <div
      class="h-112 w-full bg-banner-sm bg-cover bg-center bg-no-repeat xl:h-197 xl:bg-banner"
    >
      <div
        class="container flex h-full items-center justify-center pt-8 xl:justify-start xl:pl-11"
      >
        <h2 class="text-xl font-bold text-dark-grey xl:text-3xl">
          你的創意，從此開始
        </h2>
      </div>
    </div>
    <div class="bg-[#F7F2EB]">
      <div class="bg-feature-sm bg-no-repeat xl:bg-feature">
        <div class="container pt-26 pb-26 xl:px-28 xl:pt-60 xl:pb-40">
          <h2
            class="mb-5 text-center text-xl font-bold text-dark-grey xl:mb-10 xl:text-3xl"
          >
            屬於你的創意發想基地
          </h2>
          <p
            class="xl:px-auto text-normal px-3 text-center text-mid-grey xl:text-2xl"
          >
            點子盒結合卡片盒筆記的特性，讓您隨時隨地將突然想到的點子記錄下來，並能依照您的想法使其互相連結，配合各式生產力工具，帶來獨特的體驗
          </p>
        </div>
        <div class="container pt-12 pb-12 xl:pb-50 xl:pt-25">
          <h2
            class="xl:px-auto mb-20 px-13 text-center text-xl font-bold text-dark-grey xl:mb-25 xl:text-3xl"
          >
            為達成您的獨特體驗，我們為您提供下述功能
          </h2>
          <div class="grid grid-cols-1 xl:grid-cols-4">
            <div class="mb-20 xl:mb-0">
              <div
                class="mx-auto mb-5 h-30 w-30 rounded-full bg-feature-1 bg-cover bg-center xl:mb-10 xl:h-64 xl:w-64"
              ></div>
              <h3
                class="mb-6 text-center text-lg font-medium xl:mb-7 xl:text-2xl"
              >
                點子匣
              </h3>
              <p
                class="text-normal mx-auto mb-3 w-fit rounded-1p25 bg-secondary py-1 px-4 text-primary xl:mb-6 xl:text-xl"
              >
                創造卡片，製造連結
              </p>
              <p
                class="text-normal px-7p5 text-justify text-mid-grey xl:text-xl"
              >
                把你的點子變成創意卡片，收藏進點子匣當中，並且依照想法將互相連結，成為獨一無二的想法資料庫
              </p>
            </div>
            <div class="mb-20 xl:mb-0">
              <div
                class="mx-auto mb-5 h-30 w-30 rounded-full bg-feature-2 bg-cover bg-center xl:mb-10 xl:h-64 xl:w-64"
              ></div>
              <h3
                class="mb-6 text-center text-lg font-medium xl:mb-7 xl:text-2xl"
              >
                創意桌
              </h3>
              <p
                class="text-normal mx-auto mb-3 w-fit rounded-1p25 bg-secondary py-1 px-4 text-primary xl:mb-6 xl:text-xl"
              >
                組合創意，創造無限
              </p>
              <p
                class="text-normal px-7p5 text-justify text-mid-grey xl:text-xl"
              >
                隨心所欲組合點子匣內的創意卡片，放進九宮格並加上一些想法，進一步昇華卡片間的連結，創造無限可能
              </p>
            </div>
            <div class="mb-20 xl:mb-0">
              <div
                class="mx-auto mb-5 h-30 w-30 rounded-full bg-feature-3 bg-cover bg-center xl:mb-10 xl:h-64 xl:w-64"
              ></div>
              <h3
                class="mb-6 text-center text-lg font-medium xl:mb-7 xl:text-2xl"
              >
                計畫板
              </h3>
              <p
                class="text-normal mx-auto mb-3 w-fit rounded-1p25 bg-secondary py-1 px-4 text-primary xl:mb-6 xl:text-xl"
              >
                計畫安排，循序漸進
              </p>
              <p
                class="text-normal px-7p5 text-justify text-mid-grey xl:text-xl"
              >
                透過計畫板將你的創意展開成具體的計劃，設定時程表、作業細節、里程碑一應俱全，成為您專案管理的得力助手
              </p>
            </div>
            <div>
              <div
                class="mx-auto mb-5 h-30 w-30 rounded-full bg-feature-4 bg-cover bg-center xl:mb-10 xl:h-64 xl:w-64"
              ></div>
              <h3
                class="mb-6 text-center text-lg font-medium xl:mb-7 xl:text-2xl"
              >
                展示間
              </h3>
              <p
                class="text-normal mx-auto mb-3 w-fit rounded-1p25 bg-secondary py-1 px-4 text-primary xl:mb-6 xl:text-xl"
              >
                分享空間，社群互動
              </p>
              <p
                class="text-normal px-7p5 text-justify text-mid-grey xl:text-xl"
              >
                將你的創意分享給所有人，或者是做為小圈圈的秘密分享給你的親朋好友，為您提供創意的分享空間
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="bg-[#F2F1F1]">
      <div class="container py-15 xl:py-30">
        <h2 class="mb-5 text-center text-xl font-bold xl:mb-6 xl:text-3xl">
          價格實惠讓您輕鬆負擔
        </h2>
        <p
          class="text-normal xl:px-auto mb-10 px-3 text-center font-medium text-mid-grey xl:mb-20 xl:text-2xl"
        >
          我們提供多種等級的訂閱方式，使用者可依照需求挑選最適合的方案，<br
            class="hidden xl:block"
          />符合您的預算，創造不受限！
        </p>
        <div class="mb-20 grid grid-cols-1 gap-6 xl:grid-cols-3">
          <div
            class="group rounded-p625 bg-white py-22p5 shadow-pricing hover:-m-p1875 hover:border-pricing hover:border-primary xl:py-25"
          >
            <span
              class="material-symbols-outlined mb-5 block text-center text-64 text-mid-grey group-hover:text-primary xl:mb-7 xl:text-90"
            >
              sentiment_satisfied
            </span>
            <p
              class="mb-4 text-center text-lg font-bold text-mid-grey group-hover:text-primary xl:mb-6 xl:text-2xl"
            >
              一般使用者
            </p>
            <p class="text-center text-xl text-mid-grey xl:text-2xl">
              免費使用
            </p>
          </div>
          <div
            class="group rounded-p625 bg-white py-22p5 shadow-pricing hover:-m-p1875 hover:border-pricing hover:border-primary xl:py-25"
          >
            <span
              class="material-symbols-outlined mb-5 block text-center text-64 text-mid-grey group-hover:text-primary xl:mb-7 xl:text-90"
            >
              person
            </span>
            <p
              class="mb-4 text-center text-lg font-bold text-mid-grey group-hover:text-primary xl:mb-6 xl:text-2xl"
            >
              個人使用者
            </p>
            <p class="text-center text-xl text-mid-grey xl:text-2xl">360/月</p>
          </div>
          <div
            class="group rounded-p625 bg-white py-22p5 shadow-pricing hover:-m-p1875 hover:border-pricing hover:border-primary xl:py-25"
          >
            <span
              class="material-symbols-outlined mb-5 block text-center text-64 text-mid-grey group-hover:text-primary xl:mb-7 xl:text-90"
            >
              group
            </span>
            <p
              class="mb-4 text-center text-lg font-bold text-mid-grey group-hover:text-primary xl:mb-6 xl:text-2xl"
            >
              團隊使用者
            </p>
            <p class="text-center text-xl text-mid-grey xl:text-2xl">
              依照使用人數調整
            </p>
          </div>
        </div>
        <RouterLink
          class="mx-auto block w-fit rounded-p625 bg-primary px-15 py-4 text-xl text-white xl:text-2xl"
          to="#"
          >瞭解更多</RouterLink
        >
      </div>
    </div>
    <div class="bg-white">
      <div class="container py-15 xl:py-30">
        <h2 class="mb-10 text-center text-xl font-bold xl:mb-16 xl:text-3xl">
          點子分享
        </h2>
        <div class="mb-10 grid grid-cols-1 gap-6 xl:mb-0 xl:grid-cols-3">
          <div class="rounded-1p25 px-4 pt-4 pb-8 shadow-share">
            <div
              class="mb-8 h-60 rounded-1p25 bg-share-1 bg-cover bg-center"
            ></div>
            <div class="mx-2">
              <h3 class="mb-3 text-lg font-bold xl:text-2xl">點子盒</h3>
              <div class="mb-3 flex">
                <span
                  class="material-symbols-outlined mr-1 text-xl text-primary"
                >
                  emoji_objects
                </span>
                <span class="text-normal text-primary xl:text-xl"
                  >點子創意</span
                >
              </div>
              <p class="text-normal text-mid-grey xl:text-lg">
                點子盒結合卡片盒筆記的特性，讓您隨時隨地將突然想到的點子記錄下來，並能依照您的想法使其互相連結，配合各式生產力工具，帶來獨特的體驗
              </p>
            </div>
          </div>
          <div class="rounded-1p25 px-4 pt-4 pb-8 shadow-share">
            <div
              class="mb-8 h-60 rounded-1p25 bg-share-2 bg-cover bg-center"
            ></div>
            <div class="mx-2">
              <h3 class="mb-3 text-lg font-bold xl:text-2xl">紛饗-店家資訊</h3>
              <div class="mb-3 flex">
                <span
                  class="material-symbols-outlined mr-1 text-xl text-primary"
                >
                  sunny
                </span>
                <span class="text-normal text-primary xl:text-xl"
                  >紛饗科技</span
                >
              </div>
              <p class="text-normal text-mid-grey xl:text-lg">
                排解您的選擇困難，結合隨機選擇器以及店家資訊，簡化評論過程，使評價更有參考價值，優化您的外食體驗。
              </p>
            </div>
          </div>
          <div class="rounded-1p25 px-4 pt-4 pb-8 shadow-share">
            <div
              class="mb-8 h-60 rounded-1p25 bg-share-3 bg-cover bg-center"
            ></div>
            <div class="mx-2">
              <h3 class="mb-3 text-lg font-bold xl:text-2xl">點子盒</h3>
              <div class="mb-3 flex">
                <span
                  class="material-symbols-outlined mr-1 text-xl text-primary"
                >
                  emoji_objects
                </span>
                <span class="text-normal text-primary xl:text-xl"
                  >點子創意</span
                >
              </div>
              <p class="text-normal text-mid-grey xl:text-lg">
                點子盒結合卡片盒筆記的特性，讓您隨時隨地將突然想到的點子記錄下來，並能依照您的想法使其互相連結，配合各式生產力工具，帶來獨特的體驗
              </p>
            </div>
          </div>
        </div>
        <RouterLink
          class="mx-auto block w-fit rounded-p625 bg-primary px-15 py-4 text-xl text-white xl:hidden"
          to="#"
          >瞭解更多</RouterLink
        >
      </div>
    </div>
  </main>
</template>
