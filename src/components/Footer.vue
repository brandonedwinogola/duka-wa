<script setup>
</script>

<template>
    <div class="grid grid-cols-1 place-items-center sm:grid-cols-2 md:grid-cols-3  sm:place-items-center gap-5 z-10 relative bottom-0 right-0 left-0 bg-slate-200 p-8 md:mx-4 md:rounded-t-lg mt-20 font-open-sans">
        <div class="w-60 h-full">
            <h2 class=" text-emerald-800 font-extrabold mb-5"><RouterLink to="/">M-duka</RouterLink></h2>
            <p>Find all items you need in one place. Happy shopping!</p>
        </div>
        <div class="w-60 h-full">
            <h2 class=" text-emerald-800 font-extrabold mb-5">SHOP</h2>
            <p class="pb-1"><RouterLink class="text-black" to="/categories">Categories</RouterLink></p>
            <p class="pb-1"><RouterLink class="text-black" to="/new-items">What's new</RouterLink></p>
            <p class="pb-1">Discounts</p>
        </div>
        <div class="w-60 flex flex-col h-full">
            <h2 class=" text-emerald-800 font-extrabold mb-5">Payment methods</h2>
            <div class="flex flex-row items-center content-start">
                <img class="w-16 pr-2" src="../assets/MpesaLogo.png" alt="">
            <img class="w-16 " src="../assets/paypal.png" alt="">
            </div>
        </div>
    </div>
</template>