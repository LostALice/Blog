<template>
    <div class="flex h-screen overflow-hidden relative">
        <div class="absolute top left-1/2">
            <h1 class="mix-blend-difference text-black z-50">
                asd
            </h1>
        </div>
        <div class="w-1/2 bg-black hover:w-full duration-300 ease-in-out">
            <a href="#">
                <div class="h-full bg-black p-8 trapezoids grid place-content-evenly">
                    <div class="bg-black text-white">
                        <h1 class="text-2xl font-bold mb-4">May Be Nothing Here</h1>
                    </div>
                </div>
            </a>
        </div>
        <div class="w-1/2 bg-white hover:w-full duration-300 ease-in-out">
            <a href="#">
                <div class="h-full bg-white p-8 trapezoids grid place-content-evenly">
                    <div class="bg-white text-black">
                        <h1 class="text-2xl font-bold mb-4">May Be Something Here</h1>
                    </div>
                </div>
            </a>
        </div>
    </div>
    <!-- <div class="test overflow-hidden"></div> -->
</template>

<script setup lang="ts"></script>

<style>
.trapezoids {
    backface-visibility: hidden;
    transform: skew(10deg, 0);
    overflow: hidden;
}

.trapezoids div {
    backface-visibility: hidden;
    transform: skew(-10deg, 0);
    overflow: hidden;
}
</style>