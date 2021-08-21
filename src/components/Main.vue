<template>
    <!--
  Welcome to Tailwind Play, the official Tailwind CSS playground!

  Everything here works just like it does when you're running Tailwind locally
  with a real build pipeline. You can customize your config file, use features
  like `@apply`, or even add third-party plugins.

  Feel free to play with this example if you're just learning, or trash it and
  start from scratch if you know enough to be dangerous. Have fun!
-->
    <div class="flex grid flex-col items-center justify-center min-h-screen py-6 bg-gray-100 sm:py-12">
        <div class="max-w-xl">
            <div class="grid grid-cols-4 gap-6 text-gray-700">
                <div
                    class="flex flex-col items-center justify-center col-span-1 p-8 space-y-1 border-4 whitespace-nowrap rounded-xl"
                >
                    <div class="font-semibold tracking-wider uppercase">Maroon 5</div>
                    <div class="text-sm font-semibold text-gray-500 text-opacity-50">OverExposed</div>
                </div>
                <div
                    class="col-span-1 p-1 ease-linear shadow-xl select-none bg-gradient-to-b to-red-500 from-pink-600 hover:scale-110 rounded-2xl"
                >
                    <div
                        class="flex flex-col items-center justify-center p-8 space-y-1 bg-gray-100 whitespace-nowrap rounded-xl"
                    >
                        <div class="font-semibold tracking-wider uppercase">B.O.B 5</div>
                        <div class="text-sm font-semibold text-gray-500 text-opacity-50">Strange Clouds</div>
                    </div>
                </div>
                <div
                    class="flex flex-col items-center justify-center col-span-1 p-8 space-y-1 border-4 whitespace-nowrap rounded-xl"
                >
                    <div class="font-semibold tracking-wider uppercase">Maroon 5</div>
                    <div class="text-sm font-semibold text-gray-500 text-opacity-50">OverExposed</div>
                </div>
                <div
                    class="flex flex-col items-center justify-center col-span-1 p-8 space-y-1 border-4 whitespace-nowrap rounded-xl"
                >
                    <div class="font-semibold tracking-wider uppercase">Maroon 5</div>
                    <div class="text-sm font-semibold text-gray-500 text-opacity-50">OverExposed</div>
                </div>
                <div
                    class="flex flex-col items-center justify-center col-span-1 p-8 space-y-1 border-4 whitespace-nowrap rounded-xl"
                >
                    <div class="font-semibold tracking-wider uppercase">Maroon 5</div>
                    <div class="text-sm font-semibold text-gray-500 text-opacity-50">OverExposed</div>
                </div>
                <div
                    class="flex flex-col items-center justify-center col-span-1 p-8 space-y-1 border-4 whitespace-nowrap rounded-xl"
                >
                    <div class="font-semibold tracking-wider uppercase">Maroon 5</div>
                    <div class="text-sm font-semibold text-gray-500 text-opacity-50">OverExposed</div>
                </div>
                <div
                    class="col-span-1 p-1 bg-gradient-to-b to-blue-500 from-indigo-600 hover:scale-110 select-non rounded-2xl shadow-"
                >
                    <div
                        class="flex flex-col items-center justify-center p-8 space-y-1 bg-gray-100 whitespace-nowrap rounded-xl"
                    >
                        <div class="font-semibold tracking-wider uppercase">B.O.B 5</div>
                        <div class="text-sm font-semibold text-gray-500 text-opacity-50">Strange Clouds</div>
                    </div>
                </div>
                <div
                    class="flex flex-col items-center justify-center col-span-1 p-8 space-y-1 border-4 whitespace-nowrap rounded-xl"
                >
                    <div class="font-semibold tracking-wider uppercase">Maroon 5</div>
                    <div class="text-sm font-semibold text-gray-500 text-opacity-50">OverExposed</div>
                </div>

                <div
                    class="col-span-1 p-1 shadow-xl select-none bg-gradient-to-b to-green-500 from-green-300 hover:scale-110 rounded-2xl"
                >
                    <div
                        class="flex flex-col items-center justify-center p-8 space-y-1 bg-gray-100 whitespace-nowrap rounded-xl"
                    >
                        <div class="font-semibold tracking-wider uppercase">B.O.B 5</div>
                        <div class="text-sm font-semibold text-gray-500 text-opacity-50">Strange Clouds</div>
                    </div>
                </div>

                <div
                    class="flex flex-col items-center justify-center col-span-1 p-8 space-y-1 border-4 whitespace-nowrap rounded-xl"
                >
                    <div class="font-semibold tracking-wider uppercase">Maroon 5</div>
                    <div class="text-sm font-semibold text-gray-500 text-opacity-50">OverExposed</div>
                </div>
                <div
                    class="flex flex-col items-center justify-center col-span-1 p-8 space-y-1 border-4 whitespace-nowrap rounded-xl"
                >
                    <div class="font-semibold tracking-wider uppercase">Maroon 5</div>
                    <div class="text-sm font-semibold text-gray-500 text-opacity-50">OverExposed</div>
                </div>
                <div
                    class="flex flex-col items-center justify-center col-span-1 p-8 space-y-1 border-4 whitespace-nowrap rounded-xl"
                >
                    <div class="font-semibold tracking-wider uppercase">Maroon 5</div>
                    <div class="text-sm font-semibold text-gray-500 text-opacity-50">OverExposed</div>
                </div>
            </div>
        </div>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
    name: 'Main',
    props: {
        msg: String,
    },
})
</script>
