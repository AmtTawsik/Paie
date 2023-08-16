<template>
    <div class="w-11/12 mx-auto py-10 md:py-20">
        <h2 class="text-2xl md:text-4xl font-bold md:w-5/12">HRIS Technology that benefits present & future</h2>
        <section class="grid grid-cols-1 md:grid-cols-3 mt-16 gap-5">
            <div class="p-4">
                <img :src="handtime" alt="">
                <h5 class="text-2xl font-bold my-2">Save Operational Costs</h5>
                <p class="text-lg text-gray-600">With a paperless HRIS system, the operational costs incurred by conventional HR activities can be more economical.</p>
                <div class="w-8/12 ml-1 my-5">
                    <hr>
                </div>
                <h2 class="text-5xl font-bold">+40%</h2>
                <p class="text-lg text-gray-800 font-semibold mt-5 border-b-2 border-gray-700 border-dotted w-fit">Budget Saving</p>
            </div>
            <div class="p-4">
                <img :src="paper" alt="">
                <h5 class="text-2xl font-bold my-2">Organized HR Data</h5>
                <p class="text-lg text-gray-600">Company owners can access all employee data, HR activities and all reports in an attractive graphical analysis view.</p>
                <div class="w-8/12 ml-1 my-5">
                    <hr>
                </div>
                <h2 class="text-5xl font-bold">+35%</h2>
                <p class="text-lg text-gray-800 font-semibold mt-5 border-b-2 border-gray-700 border-dotted w-fit">Data Accuracy</p>
            </div>
            <div class="p-4">
                <img :src="mobile" alt="">
                <h5 class="text-2xl font-bold my-2">Accurate & Fast Process</h5>
                <p class="text-lg text-gray-600">The Paie finance system is provides us the accurate data when reports for payroll and claims made by employees.</p>
                <div class="w-8/12 ml-1 my-5">
                    <hr>
                </div>
                <h2 class="text-5xl font-bold">+70%</h2>
                <p class="text-lg text-gray-800 font-semibold mt-5 border-b-2 border-gray-700 border-dotted w-fit">Claim Efficiency</p>
            </div>
        </section>
    </div>
</template>

<script setup>
import handtime from '../../assets/images/handtime.png'
import paper from '../../assets/images/paper.png'
import mobile from '../../assets/images/mobile.png'
</script>