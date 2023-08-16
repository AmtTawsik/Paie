<template>
    <div class="bg-[#FEF9EC] py-10 md:py-20">
        <h2 class="text-center text-2xl font-bold md:text-4xl">Payroll so powerful it can run itself</h2>
        <p class="text-lg text-center text-gray-600 md:w-5/12 mx-auto mt-5">Paie syncs all your business's HR data with payroll, so you never have to use a calculator or manually enter data, like hours and deductions.</p>
        <section class="w-11/12 mx-auto my-20 md:my-36 grid md:grid-cols-2 gap-5 items-center">
            <div>
                <img class="rounded-lg" :src="dashboard2" alt="">
            </div>
            <div class="md:px-28">
                <img class="w-12" :src="one" alt="">
                <h5 class="text-2xl font-bold my-3">Payroll List</h5>
                <p class="text-gray-600 text-lg font-semibold">Pay employees accurately, on time, every pay run. Once your employee data is in our system, Rippling takes care of the rest.</p>
            </div>
        </section>
        <section class="w-11/12 mx-auto my-20 md:my-36 grid md:grid-cols-2 gap-5 items-center">
            <div class="md:hidden">
                <img class="rounded-lg" :src="dashboard3" alt="">
            </div>
            <div class="md:px-28">
                <img class="w-12" :src="two" alt="">
                <h5 class="text-2xl font-bold my-3">Run Sayroll in 90 Seconds</h5>
                <p class="text-gray-600 text-lg font-semibold">Pay employees accurately, on time, every pay run. Once your employee data is in our system, Rippling takes care of the rest.</p>
            </div>
            <div class="md:flex hidden">
                <img class="rounded-lg" :src="dashboard3" alt="">
            </div>
        </section>
        <section class="w-11/12 mx-auto my-20 md:my-36 grid md:grid-cols-2 gap-5 items-center">
            <div>
                <img class="rounded-lg" :src="dashboard4" alt="">
            </div>
            <div class="md:px-28">
                <img class="w-12" :src="three" alt="">
                <h5 class="text-2xl font-bold my-3">Review Payroll</h5>
                <p class="text-gray-600 text-lg font-semibold">Pay employees accurately, on time, every pay run. Once your employee data is in our system, Rippling takes care of the rest.</p>
            </div>
        </section>
        <section class="w-11/12 mx-auto my-20 md:my-36 grid md:grid-cols-2 gap-5 items-center">
            <div class="md:hidden">
                <img class="rounded-lg" :src="dashboard5" alt="">
            </div>
            <div class="md:px-28">
                <img class="w-12" :src="four" alt="">
                <h5 class="text-2xl font-bold my-3">Payroll Report</h5>
                <p class="text-gray-600 text-lg font-semibold">Pay employees accurately, on time, every pay run. Once your employee data is in our system, Rippling takes care of the rest.</p>
            </div>
            <div class="md:flex hidden">
                <img class="rounded-lg" :src="dashboard5" alt="">
            </div>
        </section>
    </div>
</template>

<script setup>
import dashboard2 from '../../assets/images/dashboard2.png'
import dashboard3 from '../../assets/images/dashboard3.jpg'
import dashboard4 from '../../assets/images/dashboard4.png'
import dashboard5 from '../../assets/images/dashboard5.jpg'
import one from '../../assets/images/one.png'
import two from '../../assets/images/two.png'
import three from '../../assets/images/three.png'
import four from '../../assets/images/four.png'
</script>