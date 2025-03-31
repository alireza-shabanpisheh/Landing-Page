<template>
  <div>
    <HeaderTop></HeaderTop>
    <div class="relative">
      <HeaderMenu></HeaderMenu>
      <div class="absolute top-[0] left-0 z-[-1]">
        <img src="../assets/left.png" alt="" />
      </div>
      <div class="absolute top-0 right-0 z-[-1] max-xl:hidden">
        <img src="../assets/right.png" alt="" />
      </div>

      <div class="flex flex-col gap-14 justify-center items-center mt-[6rem]">
        <div class="text-white">
          <p class="lg:text-[4.375rem] md:text-[3.5rem] sm:text-[2rem] max-sm:text-[2rem] text-center">Powerful for developers.</p>
          <p class="lg:text-[4.25rem] md:text-[3.5rem] sm:text-[2rem] max-sm:text-[2rem] text-center">Fast for everyone.</p>
        </div>

        <p class="lg:text-[1.3125rem] text-white sm:text-[1rem] max-sm:text-[1rem] text-center">
          Bring blockchain to the people. Solana supports experiences<br />for
          power users, new consumers, and everyone in between.
        </p>

        <div class="flex gap-4 max-sm:flex-col">
          <ButtonPurle :text="purpleBtn" />
          <ButtonBlack :text2="blackBtn"></ButtonBlack>
        </div>
      </div>
    </div>
  </div>

  <div class="flex flex-col justify-center items-center gap-11 mt-24">
    <p class="text-[#618ADC] max-sm:text-center">
      Powering tools and integrations from companies all around the world
    </p>
    <div class="flex justify-center items-center gap-10 max-xl:flex-wrap">
      <div>
        <img src="../assets/pic1.png" alt="" />
      </div>
      <div>
        <img src="../assets/pic2.png" alt="" />
      </div>
      <div>
        <img src="../assets/pic3.png" alt="" />
      </div>
      <div>
        <img src="../assets/pic4.png" alt="" />
      </div>
      <div>
        <img src="../assets/pic5.png" alt="" />
      </div>
      <div>
        <img src="../assets/pic6.png" alt="" />
      </div>
      <div>
        <img src="../assets/pic7.png" alt="" />
      </div>
    </div>
  </div>

  <div>
    <div class="w-full relative">
      <img
        src="../assets/mainPic.png"
        class="w-full h-auto object-cover absolute z-[-1]"
        alt=""/>
    </div>
    <div class="flex justify-center items-center gap-44 max-lg:flex-col max-lg:gap-10 py-32">
      <p class="text-[#FFFFFF] text-[2.375rem] max-sm:text-[2rem]">
        Join a community of millions
      </p>
      <div class="flex flex-col justify-center max-sm:gap-4">
        <div>
          <span
            class="max-sm:text-[3rem] text-[6.3125rem] bg-gradient-to-r from-[#8C01FA] to-[#19FB9B] bg-clip-text text-transparent"
            >11.5M+</span
          >
          <p class="text-[#C4C4C4]">Active accounts</p>
        </div>
        <div>
          <span
            class="max-sm:text-[3rem] text-[6.3125rem] bg-gradient-to-r from-[#8C01FA] to-[#19FB9B] bg-clip-text text-transparent"
            >21.9M</span
          >
          <p class="text-[#C4C4C4]">NFTs minted</p>
        </div>
        <div>
          <span
            class="max-sm:text-[3rem] text-[6.3125rem] bg-gradient-to-r from-[#8C01FA] to-[#19FB9B] bg-clip-text text-transparent"
            >$0.00025</span
          >
          <p class="text-[#C4C4C4]">Average cost per transaction</p>
        </div>
      </div>
    </div>

    <div class="flex items-center justify-center gap-24 max-lg:flex-col">
      <div>
        <span class="text-[#FFFFFF] text-[2.5rem]">Made for<br />mass adoption.</span>
        <p class="text-[#FFFFFF]">Live data</p>
      </div>

      <div class="flex flex-col gap-11">
        <div class="bg-black/28 rounded-[1.5rem]">
          <div class="p-[2rem] flex flex-col gap-2.5">
            <span class="text-[#FFFFFF] text-[1.75rem]">Fast</span>
            <p class="text-[#FFFFFF]">
              Don’t keep your users waiting.<br />Solana has block times of
              400<br />milliseconds — and as hardware<br />
              gets faster, so will the network.
            </p>
            <span class="text-[#FFFFFF] text-[1.75rem]">3,969</span>
            <p class="text-[#FFFFFF]">Transactions per second</p>
          </div>
        </div>
        <div class="bg-black/28 rounded-[1.5rem]">
          <div class="p-[2rem] flex flex-col gap-2.5">
            <span class="text-[#FFFFFF] text-[1.75rem]">Fast</span>
            <p class="text-[#FFFFFF]">
              Don’t keep your users waiting.<br />Solana has block times of
              400<br />milliseconds — and as hardware<br />
              gets faster, so will the network.
            </p>
            <span class="text-[#FFFFFF] text-[1.75rem]">3,969</span>
            <p class="text-[#FFFFFF]">Transactions per second</p>
          </div>
        </div>
      </div>

      <div class="flex flex-col gap-11">
        <div class="bg-black/28 rounded-[1.5rem]">
          <div class="p-[2rem] flex flex-col gap-2.5">
            <span class="text-[#FFFFFF] text-[1.75rem]">Fast</span>
            <p class="text-[#FFFFFF]">
              Don’t keep your users waiting.<br />Solana has block times of
              400<br />milliseconds — and as hardware<br />
              gets faster, so will the network.
            </p>
            <span class="text-[#FFFFFF] text-[1.75rem]">3,969</span>
            <p class="text-[#FFFFFF]">Transactions per second</p>
          </div>
        </div>
        <div class="bg-black/28 rounded-[1.5rem]">
          <div class="p-[2rem] flex flex-col gap-2.5">
            <span class="text-[#FFFFFF] text-[1.75rem]">Fast</span>
            <p class="text-[#FFFFFF]">
              Don’t keep your users waiting.<br />Solana has block times of
              400<br />milliseconds — and as hardware<br />
              gets faster, so will the network.
            </p>
            <span class="text-[#FFFFFF] text-[1.75rem]">3,969</span>
            <p class="text-[#FFFFFF]">Transactions per second</p>
          </div>
        </div>
      </div>

  

    </div>
  </div>


  <div class="mt-32 flex flex-col gap-6">
    <div class="flex justify-center items-center gap-[25rem] max-xl:flex-col max-xl:gap-[2rem]">
        <p class="text-white text-4xl">Build for growth.</p>
        <div class="flex items-center gap-[1rem] max-sm:flex-wrap">
            <ButtonNft :text3="nftButton"></ButtonNft>
            <ButtonNft :text3="nftButton"></ButtonNft>
            <ButtonNft :text3="nftButton"></ButtonNft>
            <ButtonNft :text3="nftButton"></ButtonNft>
            <ButtonNft :text3="nftButton"></ButtonNft>
        </div>
    </div>

    <div class="flex items-center justify-center max-xl:flex-col">
        <div class="w-[550px] h-[400px] max-sm:w-[400px] max-sm:h-[250px]">
            <img class="w-full object-cover" src="../assets/manPic.png" alt="">
        </div>
        <div class="w-[550px] h-[400px] max-sm:w-[400px] max-sm:h-[250px] bg-[#1A1A1A] rounded-[5px] flex flex-col justify-center items-center gap-[2rem]">
          <div class="w-[240px]">
            <img class="w-full object-cover" src="../assets/manPicIcon.png" alt="">
          </div>
            <p class="text-white text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit.<br> Unde omnis sequi cumque aspernatur vel<br> tenetur praesentium repellat quos illo architecto?</p>
        </div>
    </div>

    <div class="flex justify-center gap-52 max-lg:flex-wrap max-lg:gap-5">
        <img src="../assets/manone.png" alt="">
        <img src="../assets/mantwo.png" alt="">
        <img src="../assets/mantree.png" alt="">
        <img src="../assets/manfour.png" alt="">
    </div>
  </div>

  

  <div class="relative mt-28">
    <div>
      <img class="absolute z-[-1] top-0 " src="../assets/bgcSlider.png" alt="">
    </div>
    <div class="flex flex-col gap-12">
      <div class="flex flex-col gap-6">
        <p class="text-white text-[2.375rem] text-center break-words">Join a thriving community.</p>
        <SliderAnimate></SliderAnimate>
      </div>
  
      <div class="flex flex-col gap-6 items-center">
        <p class="text-white text-[2.375rem] break-words text-center">It's time to join the thousands of creators,<br>artists, and developers using Solana.</p>
        <ButtonPurle :text="purpleBtn"></ButtonPurle>
      </div>
    </div>


  </div>


  <div>
    <FooterPage></FooterPage>
  </div>

</template>

<script setup lang="ts">
import HeaderMenu from "../components/HeaderMenu.vue";
import HeaderTop from "../components/HeaderTop.vue";
import ButtonBlack from "../components/ButtonBlack.vue";
import ButtonPurle from "../components/ButtonPurple.vue";
import ButtonNft from "@/components/ButtonNft.vue";
import FooterPage from "@/components/FooterPage.vue";
import SliderAnimate from "@/components/SliderAnimate.vue";

import { ref } from "vue";

const purpleBtn = ref("Start building");
const blackBtn = ref("Read docs");
const nftButton = ref("NFts")

</script>


<style lang="scss" scoped>

</style>