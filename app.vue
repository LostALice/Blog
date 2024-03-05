<template>
    <div class="flex h-screen overflow-hidden relative">
        <!-- <div class="absolute top left-1/2">
            <h1 class="mix-blend-difference text-black z-50">
                asd
            </h1>
        </div> -->
        <div class="group w-1/2 bg-[#0a0a0a] hover:w-full duration-300 ease-in-out">
            <a href="#">
                <div class="h-full bg-black p-8 trapezoids grid place-content-evenly">
                    <div class="bg-black text-white text-center">
                        <h1 class="text-2xl font-bold mb-4">May Be Nothing Here</h1>
                        <h2 class="text-2xl font-bold mb-4 opacity-0 group-hover:opacity-100">Warabimochi wa ikaga desu ka?</h2>
                    </div>
                </div>
            </a>
        </div>
        <div class="group w-1/2 bg-white hover:w-full duration-300 ease-in-out">
            <a href="#">
                <div class="h-full bg-white p-8 trapezoids grid place-content-evenly">
                    <div class="bg-white text-black text-center">
                        <h1 class="text-2xl font-bold mb-4">May Be Something There</h1>
                        <h2 class="text-2xl font-bold mb-4 opacity-0 group-hover:opacity-100">Do You Know to Magic?</h2>
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