<template>
    <div class="w-screen h-screen flex-col">
            <div class="h-[50px] w-full bg-lime-800 flex-row flex gap-4">
                <img class="w-[40px]" src="../../assets/logo.svg" alt="">
                <h1>
                    SD Muhammadiyah <br> Tamantirto
                </h1>
            </div>
        <div class="flex w-full h-full">
            <div class="w-[325px] h-full bg-gray-200 text-center justify-center">
                <div class="h-full bg-green-950">
                    Menu
                </div>
            </div>
            <div class="w-full h-full">
                <div class="h-full bg-gray-400">
                    content
                </div>
            </div>
        </div>
    </div>
</template>
<script lang="ts">
export default {

}
</script>
<style>
.bg-gray-400 {
    --tw-bg-opacity: 1;
    background-color: rgb(230, 230, 230);
}

.bg-lime-800 {
    --tw-bg-opacity: 1;
    background-color: rgb(95, 141, 78);
}

.bg-green-950 {
    --tw-bg-opacity: 1;
    background-color: rgb(40, 84, 48);
}
</style>