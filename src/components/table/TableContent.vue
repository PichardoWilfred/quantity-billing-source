<template>
    <main class="flex max-lg:flex-col justify-start items-start content-start lg:flex-wrap bg-gray-1 overflow-y-scroll flex-grow-[2] h-max">
        <div v-for="(item, index) in items" :key="index" 
        class="flex items-center justify-between flex-shrink-0 w-full lg:w-[33.33%] xl:w-[20%] px-3 py-4 bg-white hover:bg-gray-2 cursor-pointer border-r border-b border-gray-2 max-lg:last:border-white shadow-[0_1px_4px_rgba(0,0,0,0.16)]">
            <h4 class="font-bold text-lg">
                Item #{{ index + 1000 }}
            </h4>
            <input type="text" class="focus-within:outline-none w-[40%] px-3 py-2 bg-gray-1 rounded-sm">
        </div>
    </main>
    <footer class="flex justify-center max-lg:flex-col bg-white p-4 border-t-2 border-gray-3 shadow-[0_1px_4px_rgba(0,0,0,0.16)]">
        <div class="flex items-center justify-between">
            <div class="flex">
                <button class="flex items-center border-2 px-3 py-2 rounded-md border-gray-5 text-gray-5">
                    <i class="fa-solid fa-xmark text-xl mr-3"></i>
                    <span class="text-md font-semibold">
                        Eliminar item
                    </span>
                </button>
            </div>
            <div class="flex flex-col lg:order-2 items-end ml-auto">
                <h4 class="text-gray-4 text-md font-bold">
                    TOTAL
                </h4>
                <h3 class="text-dark text-3xl font-bold">
                    100.00
                </h3>
            </div>
        </div>
        <div class="flex lg:w-[380px] lg:items-center lg:order-1 mt-2 lg:mx-auto">
            <input type="text" class="lg:h-[40px] pl-3 border-gray-4 border mr-2 flex-grow-[2] rounded-md focus-within:outline-none">
            <button class="bg-black hover:bg-black-2 text-white rounded-md flex-grow-2 ">
                <i class="fa-solid fa-paper-plane p-3 px-5"></i>
            </button>
        </div>
    </footer>
</template>
<script>
export default {
    name: 'TableContent',
    data() {
        return {
            items: [
                20,
                20,
                20,
                20,
                20,
                20,
                20,
                20,
                20,
                20,
                20,
                20,
                20,
                20,
                20,
                // 20,
                // 20,
                // 20,
                // 20,
                // 20,
                // 20,
                // 20,
                // 20,
                // 20,
                // 20,
                // 20,
                // 20,
                // 20,
                // 20,
            ]
        }
    },
}
</script>
<style scoped>
    
</style>