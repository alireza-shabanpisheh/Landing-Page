<template>
  <div>
    <header class='flex border-b bg-black/60 font-sans min-h-[70px] tracking-wide relative z-50'>
      <div class='flex flex-wrap items-center justify-between sm:px-10 px-4 py-3 gap-4 w-full max-w-screen-xl mx-auto'>
        <a href="javascript:void(0)" class="max-sm:hidden"><img src="../assets/inoLogoOrg.png" alt="logo" class='w-32' />
        </a>
        <a href="javascript:void(0)" class="hidden max-sm:block"><img src="../assets/inoLogoOrg.png" alt="logo" class='w-32' />
        </a>

        <div id="collapseMenu"
          class='max-lg:hidden lg:!block max-lg:before:fixed max-lg:before:bg-black max-lg:before:opacity-50 max-lg:before:inset-0 max-lg:before:z-50'>
          <button id="toggleClose" class='lg:hidden fixed top-2 right-4 z-[100] rounded-full bg-white w-9 h-9 flex items-center justify-center border'>
            <svg xmlns="http://www.w3.org/2000/svg" class="w-3.5 h-3.5 fill-black" viewBox="0 0 320.591 320.591">
              <path
                d="M30.391 318.583a30.37 30.37 0 0 1-21.56-7.288c-11.774-11.844-11.774-30.973 0-42.817L266.643 10.665c12.246-11.459 31.462-10.822 42.921 1.424 10.362 11.074 10.966 28.095 1.414 39.875L51.647 311.295a30.366 30.366 0 0 1-21.256 7.288z"
                data-original="#000000"></path>
              <path
                d="M287.9 318.583a30.37 30.37 0 0 1-21.257-8.806L8.83 51.963C-2.078 39.225-.595 20.055 12.143 9.146c11.369-9.736 28.136-9.736 39.504 0l259.331 257.813c12.243 11.462 12.876 30.679 1.414 42.922-.456.487-.927.958-1.414 1.414a30.368 30.368 0 0 1-23.078 7.288z"
                data-original="#000000"></path>
            </svg>
          </button>

          <ul
            class='lg:flex lg:gap-x-10 max-lg:space-y-3 max-lg:fixed max-lg:bg-black max-lg:w-1/2 max-lg:min-w-[300px] max-lg:top-0 max-lg:left-0 max-lg:p-6 max-lg:h-full max-lg:shadow-md max-lg:overflow-auto z-50'>
            <li class='mb-6 hidden max-lg:block'>
              <a href="javascript:void(0)"><img src="../assets/inoLogoOrg.png" alt="logo" class='w-36' />
              </a>
            </li>

            <li class='group max-lg:border-b max-lg:py-3 relative'>
              <a href='javascript:void(0)'
                class='hover:text-[#fff] text-[#fff] text-[15px] font-bold lg:hover:fill-[#007bff] block'>Learn<svg
                  xmlns="http://www.w3.org/2000/svg" fill="#fff" width="16px" height="16px" class="ml-1 inline-block"
                  viewBox="0 0 24 24">
                  <path
                    d="M12 16a1 1 0 0 1-.71-.29l-6-6a1 1 0 0 1 1.42-1.42l5.29 5.3 5.29-5.29a1 1 0 0 1 1.41 1.41l-6 6a1 1 0 0 1-.7.29z"
                    data-name="16" data-original="#000000" />
                </svg>
              </a>
              <ul
                class='absolute shadow-lg bg-black space-y-3 lg:top-5 max-lg:top-8 -left-6 min-w-[250px] z-50 max-h-0 overflow-hidden group-hover:opacity-100 group-hover:max-h-[700px] px-6 group-hover:pb-4 group-hover:pt-6 transition-all duration-500'>
                <li class='border-b py-2 '><a href='javascript:void(0)'
                  class='hover:text-[#007bff] text-[#fff] text-[15px] font-bold block'>About</a></li>
                <li class='border-b py-2 '><a href='javascript:void(0)'
                  class='hover:text-[#007bff] text-[#fff] text-[15px] font-bold block'>Contact</a></li>
                <li class='border-b py-2 '><a href='javascript:void(0)'
                  class='hover:text-[#007bff] text-[#fff] text-[15px] font-bold block'>Login</a></li>
                <li class='border-b py-2 '><a href='javascript:void(0)'
                  class='hover:text-[#007bff] text-[#fff] text-[15px] font-bold block'>Sign up</a></li>
                <li class='border-b py-2 '><a href='javascript:void(0)'
                  class='hover:text-[#007bff] text-[#fff] text-[15px] font-bold block'>Blog</a></li>
              </ul>
            </li>

            <li class='group max-lg:border-b max-lg:py-3 relative'>
              <a href='javascript:void(0)'
                class='hover:text-[#fff] text-[#fff] text-[15px] font-bold lg:hover:fill-[#007bff] block'>Build<svg
                  xmlns="http://www.w3.org/2000/svg" fill="#fff" width="16px" height="16px" class="ml-1 inline-block"
                  viewBox="0 0 24 24">
                  <path
                    d="M12 16a1 1 0 0 1-.71-.29l-6-6a1 1 0 0 1 1.42-1.42l5.29 5.3 5.29-5.29a1 1 0 0 1 1.41 1.41l-6 6a1 1 0 0 1-.7.29z"
                    data-name="16" data-original="#000000" />
                </svg>
              </a>
              <ul
                class='absolute shadow-lg bg-black space-y-3 lg:top-5 max-lg:top-8 -left-6 min-w-[250px] z-50 max-h-0 overflow-hidden group-hover:opacity-100 group-hover:max-h-[700px] px-6 group-hover:pb-4 group-hover:pt-6 transition-all duration-500'>
                <li class='border-b py-2 '><a href='javascript:void(0)'
                  class='hover:text-[#007bff] text-[#fff] text-[15px] font-bold block'>Foods</a></li>
                <li class='border-b py-2 '>
                  <a href='javascript:void(0)'
                    class='hover:text-[#007bff] text-[#fff] text-[15px] font-bold block'>Sale</a>
                </li>
                <li class='border-b py-2 '><a href='javascript:void(0)'
                  class='hover:text-[#007bff] text-[#fff] text-[15px] font-bold block'>Marketing</a></li>
                <li class='border-b py-2 '><a href='javascript:void(0)'
                  class='hover:text-[#007bff] text-[#fff] text-[15px] font-bold block'>Investment</a></li>
              </ul>
            </li>
            <li class='group max-lg:border-b max-lg:py-3 relative'>
              <a href='javascript:void(0)'
                class='hover:text-[#fff] text-[#fff] text-[15px] font-bold lg:hover:fill-[#007bff] block'>Network<svg
                  xmlns="http://www.w3.org/2000/svg" fill="#fff" width="16px" height="16px" class="ml-1 inline-block"
                  viewBox="0 0 24 24">
                  <path
                    d="M12 16a1 1 0 0 1-.71-.29l-6-6a1 1 0 0 1 1.42-1.42l5.29 5.3 5.29-5.29a1 1 0 0 1 1.41 1.41l-6 6a1 1 0 0 1-.7.29z"
                    data-name="16" data-original="#000000" />
                </svg>
              </a>
              <ul
                class='absolute shadow-lg bg-black space-y-3 lg:top-5 max-lg:top-8 -left-6 min-w-[250px] z-50 max-h-0 overflow-hidden group-hover:opacity-100 group-hover:max-h-[700px] px-6 group-hover:pb-4 group-hover:pt-6 transition-all duration-500'>
                <li class='border-b py-2 '><a href='javascript:void(0)'
                  class='hover:text-[#007bff] text-[#fff] text-[15px] font-bold block'>Foods</a></li>
                <li class='border-b py-2 '>
                  <a href='javascript:void(0)'
                    class='hover:text-[#007bff] text-[#fff] text-[15px] font-bold block'>Sale</a>
                </li>
                <li class='border-b py-2 '><a href='javascript:void(0)'
                  class='hover:text-[#007bff] text-[#fff] text-[15px] font-bold block'>Marketing</a></li>
                <li class='border-b py-2 '><a href='javascript:void(0)'
                  class='hover:text-[#007bff] text-[#fff] text-[15px] font-bold block'>Investment</a></li>
              </ul>
            </li>
            <li class='group max-lg:border-b max-lg:py-3 relative'>
              <a href='javascript:void(0)'
                class='hover:text-[#fff] text-[#fff] text-[15px] font-bold lg:hover:fill-[#007bff] block'>Community<svg
                  xmlns="http://www.w3.org/2000/svg" fill="#fff" width="16px" height="16px" class="ml-1 inline-block"
                  viewBox="0 0 24 24">
                  <path
                    d="M12 16a1 1 0 0 1-.71-.29l-6-6a1 1 0 0 1 1.42-1.42l5.29 5.3 5.29-5.29a1 1 0 0 1 1.41 1.41l-6 6a1 1 0 0 1-.7.29z"
                    data-name="16" data-original="#000000" />
                </svg>
              </a>
              <ul
                class='absolute shadow-lg bg-black space-y-3 lg:top-5 max-lg:top-8 -left-6 min-w-[250px] z-50 max-h-0 overflow-hidden group-hover:opacity-100 group-hover:max-h-[700px] px-6 group-hover:pb-4 group-hover:pt-6 transition-all duration-500'>
                <li class='border-b py-2 '><a href='javascript:void(0)'
                  class='hover:text-[#007bff] text-[#fff] text-[15px] font-bold block'>Foods</a></li>
                <li class='border-b py-2 '>
                  <a href='javascript:void(0)'
                    class='hover:text-[#007bff] text-[#fff] text-[15px] font-bold block'>Sale</a>
                </li>
                <li class='border-b py-2 '><a href='javascript:void(0)'
                  class='hover:text-[#007bff] text-[#fff] text-[15px] font-bold block'>Marketing</a></li>
                <li class='border-b py-2 '><a href='javascript:void(0)'
                  class='hover:text-[#007bff] text-[#fff] text-[15px] font-bold block'>Investment</a></li>
              </ul>
            </li>

            
          </ul>

        </div>

        <div class='flex items-center space-x-8 max-lg:ml-auto'>

          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 192.904 192.904" width="20px"
            class="cursor-pointer fill-[#fff] hover:fill-[#fff]">
            <path
              d="m190.707 180.101-47.078-47.077c11.702-14.072 18.752-32.142 18.752-51.831C162.381 36.423 125.959 0 81.191 0 36.422 0 0 36.423 0 81.193c0 44.767 36.422 81.187 81.191 81.187 19.688 0 37.759-7.049 51.831-18.751l47.079 47.078a7.474 7.474 0 0 0 5.303 2.197 7.498 7.498 0 0 0 5.303-12.803zM15 81.193C15 44.694 44.693 15 81.191 15c36.497 0 66.189 29.694 66.189 66.193 0 36.496-29.692 66.187-66.189 66.187C44.693 147.38 15 117.689 15 81.193z">
            </path>
          </svg>

          <button id="toggleOpen" class='lg:hidden'>
            <svg class="w-7 h-7" fill="#fff" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
              <path fill-rule="evenodd"
                d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z"
                clip-rule="evenodd"></path>
            </svg>
          </button>
        </div>
      </div>
    </header>
  </div>
</template>

<script setup lang="ts">
import { onMounted } from 'vue';

onMounted(() => {
  const toggleOpen = document.getElementById('toggleOpen') as HTMLButtonElement | null;
  const toggleClose = document.getElementById('toggleClose') as HTMLButtonElement | null;
  const collapseMenu = document.getElementById('collapseMenu') as HTMLDivElement | null;

  if (!toggleOpen || !toggleClose || !collapseMenu) return;

  function handleClick() {
  const collapseMenu = document.getElementById('collapseMenu'); // مقداردهی

  if (collapseMenu) { // بررسی مقدار null
    collapseMenu.style.display = collapseMenu.style.display === 'block' ? 'none' : 'block';
  }
}


  toggleOpen.addEventListener('click', handleClick);
  toggleClose.addEventListener('click', handleClick);
});
</script>


<style lang="scss" scoped>
</style>