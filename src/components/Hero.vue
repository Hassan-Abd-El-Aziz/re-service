<template>
    <section class="relative overflow-hidden bg-gray-50 
    py-12 px-4 sm:px-6 md:px-8 lg:py-16 lg:px-20 flex flex-col 
    lg:flex-row items-center justify-between">
        <div class="flex-1 lg:ml-28 w-full max-w-xl 
        space-y-6 relative z-20">
            <h2 class="text-4xl sm:text-5xl text-gray-900 
            text-center lg:text-left" data-aos="fade-right">
                professionals
                <span class="font-bold text-black block lg:inline"> Service</span>
            </h2>
            <div class="flex gap-3 mt-4 justify-center lg:justify-start
            " data-aos="fade-right" data-aos-delay="100">
                <Circle class="text-pink-500 w-5 h-5" />
                <Circle class="text-yellow-500 w-5 h-5" />
                <Circle class="text-green-500 w-5 h-5" />

            </div>
            <div class="flex flex-col lg:grid grid-cols-2 gap-6 lg:gap-48 
items-center lg:items-start">
                <div class="bg-white w-72 rounded-xl p-6 border border-gray-100 shadow-xl lg:shadow-2xl transition"
                    data-aos="zoom-in" data-aos-delay="200">

                    <div class="ml-4 w-10 h-10 flex items-center justify-center rounded-lg bg-pink-100 mb-4">
                        <span class="text-pink-500 text-xl">
                            <Heart class="text-pink-600 w-6 h-6" />
                        </span>
                    </div>
                    <h3 class="ml-4 text-lg font-semibold text-gray-800">Service Subtitle One</h3>
                    <p class=" ml-4 text-gray-500 text-sm mt-2">Lorem ipsum dolor sit amet, consectetur adipisicing
                        elit.</p>
                </div>
            </div>
        </div>
    </section>
</template>

<script setup>
import { Circle, Heart } from 'lucide-vue-next';
</script>