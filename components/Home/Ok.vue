<template>
    <div class="bg-[#FEF9EC] py-10 md:py-20">
        <section class="w-11/12 mx-auto grid grid-cols-1 md:grid-cols-2 gap-5 items-center">
            <div>
                <div class="flex md:hidden mb-4">
                    <img :src="ok" alt="">
                </div>
                <h2 class="text-3xl md:text-5xl font-bold">Why our customers think we're the best</h2>
                <div class="md:flex hidden mt-4">
                    <img :src="ok" alt="">
                </div>
            </div>
            <div>

                <div class="bg-white p-5 rounded-md shadow-md mb-5">
                    <div class="flex justify-between items-center">
                        <div class="flex items-center">
                            <img class="w-12 h-12 rounded-full mr-2"
                                src="https://flowbite.com/docs/images/people/profile-picture-5.jpg" alt="Rounded avatar">
                            <div>
                                <h6 class="text-gray-800 font-bold">Delbert Dicki</h6>
                                <p class="text-gray-600">HR Officer <span class="hidden md:inline-block">at mailchimp</span>
                                </p>
                            </div>
                        </div>
                        <img class="md:w-40 w-28" :src="mailchimp" alt="">
                    </div>
                    <hr class="my-5">
                    <p class="text-gray-600">"My favorite thing about Paie is the compliance aspect. They make quarterly
                        taxes, onboarding, and everything else so simple and easy, which saves me a ton of time!"</p>
                </div>

                <div class="bg-white p-5 rounded-md shadow-md mb-5">
                    <div class="flex justify-between items-center">
                        <div class="flex items-center">
                            <img class="w-12 h-12 rounded-full mr-2"
                                src="https://flowbite.com/docs/images/people/profile-picture-1.jpg" alt="Rounded avatar">
                            <div>
                                <h6 class="text-gray-800 font-bold">Chatalyne Devan</h6>
                                <p class="text-gray-600">HR Officer <span class="hidden md:inline-block">at DocuSign</span>
                                </p>
                            </div>
                        </div>
                        <img class="md:w-40 w-28" :src="docusing" alt="">
                    </div>
                    <hr class="my-5">
                    <p class="text-gray-600">"As soon as I saw how easy it was to set everything up I liked it, but the
                        first time I ever dealt with customer service is when I really knew we chose the right payroll
                        company."</p>
                </div>

                <div class="bg-white p-5 rounded-md shadow-md">
                    <div class="flex justify-between items-center">
                        <div class="flex items-center">
                            <img class="w-12 h-12 rounded-full mr-2"
                                src="https://flowbite.com/docs/images/people/profile-picture-5.jpg" alt="Rounded avatar">
                            <div>
                                <h6 class="text-gray-800 font-bold">Marshall Beer</h6>
                                <p class="text-gray-600">HR Officer <span class="hidden md:inline-block">at Basecamp</span>
                                </p>
                            </div>
                        </div>
                        <img class="md:w-40 w-28" :src="basecamp" alt="">
                    </div>
                    <hr class="my-5">
                    <p class="text-gray-600">"Paie helped me a lot especially with the attendance, so now the marketing team
                        can check in and leave with the offsite application. The payroll process is also very fast!"</p>
                </div>

            </div>
        </section>
    </div>
    <div class="bg-[#F7C343] py-10 md:py-20">
        <section class="w-11/12 mx-auto">
            <h2 class="text-3xl md:text-5xl font-bold w-7/12">Start enjoying the best experience in managing HR with PAIE</h2>
            <p class="text-lg text-gray-800 my-5 w-5/12">Learn how Paie can help you effortlessly onboard and manage your
                employess, whether you have a workforce of 2 or 2,000.</p>
            <div class="flex flex-col space-y-4 sm:flex-row sm:space-y-0 sm:space-x-4">
                <a href="#"
                    class="inline-flex justify-center items-center py-4 px-8 text-base font-medium text-center text-white bg-black hover:bg-black-600 focus:ring-4 focus:ring-black">
                    Try 14 Days for free
                </a>
                <a href="#"
                    class="inline-flex justify-center items-center py-4 px-8 text-base font-medium text-center text-black bg-none focus:ring-4 focus:ring-gray-300 border-2 border-black dark:focus:ring-black">
                    Book a Demo
                </a>
            </div>
        </section>
    </div>
</template>

<script setup>
import ok from '../../assets/images/ok.png'
import mailchimp from '../../assets/images/mailchimp.png'
import docusing from '../../assets/images/docusing.png'
import basecamp from '../../assets/images/basecamp.png'
</script>