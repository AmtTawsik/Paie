<template>
  <div>
    <nav class="bg-[#FEF9EC]">
      <div class="w-11/12 flex flex-wrap items-center justify-between mx-auto p-4">
        <a href="https://www.qualyval.com/" class="flex items-center">
          <p class="text-4xl font-bold whitespace-nowrap text-[#F7C343]">Qualyval</p>
        </a>
        <div class="flex md:order-2">
          <button type="button"
            class="inline-flex justify-center items-center py-2 px-5 text-base font-medium text-center text-black bg-none focus:ring-4 focus:ring-gray-300 border-2 border-black dark:focus:ring-black">Book a Demo</button>
          <button data-collapse-toggle="navbar-sticky" type="button"
            class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600"
            aria-controls="navbar-sticky" aria-expanded="false">
            <span class="sr-only">Open main menu</span>
            <svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 17 14">
              <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                d="M1 1h15M1 7h15M1 13h15" />
            </svg>
          </button>
        </div>
        <div class="items-center justify-between hidden w-full md:flex md:w-auto md:order-1" id="navbar-sticky">
          <ul
            class="flex flex-col p-4 md:p-0 mt-4 font-medium rounded-lg md:flex-row md:space-x-8 md:mt-0 md:border-0 dark:bg-gray-800 md:dark:bg-gray-900 dark:border-gray-700">
            
            <li>
              <a href="#"
                class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-[#F7C343] md:p-0 md:dark:hover:text-[#F7C343] dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Product</a>
            </li>
            <li>
              <a href="#"
                class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-[#F7C343] md:p-0 md:dark:hover:text-[#F7C343] dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Pricing</a>
            </li>
            <li>
              <a href="#"
                class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-[#F7C343] md:p-0 md:dark:hover:text-[#F7C343] dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Customer</a>
            </li>
            <li>
              <a href="#"
                class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-[#F7C343] md:p-0 md:dark:hover:text-[#F7C343] dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Partner</a>
            </li>
            <li>
              <a href="#"
                class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-[#F7C343] md:p-0 md:dark:hover:text-[#F7C343] dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Resources</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <slot></slot>
    <FooterComponent></FooterComponent>
  </div>
</template>

<script setup>
// import { onMounted } from 'vue'
// import { Drawer } from 'flowbite';

// onMounted(() => {
//   // setup available elements
//   const $buttonElement = document.querySelector('#button');
//   const $drawerElement = document.querySelector('#sidebar');
//   const $closeButtons = document.querySelectorAll('#closeButton');

//   // set drawer options
//   const drawerOptions = {
//     backdropClasses:
//       'bg-gray-900 bg-opacity-50 dark:bg-opacity-80 fixed inset-0 z-40',
//   };

//   // create a new drawer instance
//   if ($drawerElement) {
//     const drawer = new Drawer($drawerElement, drawerOptions);

//     // set event listeners for the button to show the drawer
//     $buttonElement.addEventListener('click', () => drawer.toggle());
//     $closeButtons.forEach((el) => {
//       el.addEventListener('click', () => drawer.hide());
//     });
//   }
// });

import { onMounted } from 'vue'
import { initFlowbite } from 'flowbite'

// initialize components based on data attribute selectors
onMounted(() => {
    initFlowbite();
})
</script>