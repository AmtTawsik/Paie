<template>
  <div class="bg-[#FEF9EC]">
    <div class="md:hidden">
      <img :src="dashboard" alt="">
    </div>
    <section class="pb-5 md:pb-0">
      <div class="pt-5 px-4 mx-auto max-w-screen-xl text-center lg:pt-10 lg:px-12">
        <h1
          class="text-2xl font-semibold tracking-tight w-10/12 mx-auto leading-none text-gray-900 md:text-6xl dark:text-white">
          Enjoy the Experience of Managing HR & Payroll at your Fingertips.
        </h1>
        <p class="my-5 text-lg font-normal text-gray-500 md:text-xl md:w-6/12 mx-auto dark:text-gray-400">Paie lets you
          easily manage your employees' payroll, benefits, expenses,
          devices, apps & more-in one place.</p>
        <div class="flex flex-col space-y-4 sm:flex-row sm:justify-center sm:space-y-0 sm:space-x-4">
          <a href="#"
            class="inline-flex justify-center items-center py-4 px-8 text-base font-medium text-center text-white bg-yellow-500 hover:bg-yellow-600 focus:ring-4 focus:ring-blue-300 dark:focus:ring-blue-900">
            Try 14 Days for free
          </a>
          <a href="#"
            class="inline-flex justify-center items-center py-4 px-8 text-base font-medium text-center text-black bg-none focus:ring-4 focus:ring-gray-300 border-2 border-black dark:focus:ring-black">
            Book a Demo
          </a>
        </div>
      </div>
    </section>
    <div class="hidden md:flex">
      <img :src="dashboard" alt="">
    </div>
  </div>
  <div class="bg-[#F7C343] py-20">
    <section class="grid md:grid-cols-2 w-11/12 gap-5 mx-auto items-center">
      <h2 class="text-2xl md:text-4xl font-semibold md:w-9/12 text-gray-900">Speed up payroll processing with other companies</h2>
      <div>
        <img :src="brand" alt="">
      </div>
    </section>
  </div>
</template>

<script setup>
import dashboard from '../../assets/images/dashboard.png'
import brand from '../../assets/images/brand.png'
</script>