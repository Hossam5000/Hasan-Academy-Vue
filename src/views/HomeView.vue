<script setup>

</script>

<template>
    <main>
        <div class="container py-15 mx-auto px-6 text-white text-center">
            <div class="content flex flex-col items-center mt-33 mb-8">
                <h2 class="text-2xl mb-4 font-semibold">ادخل رقم الهاتف</h2>
                <input
                    class="px-4 py-3 text-2xl bg-white placeholder-[#8E8E93] rounded-lg mb-6 w-88.5 text-black focus:outline-none"
                    type="number" id="phone-number" placeholder="+20...">
                <input class="block w-87.5 px-6 py-3 bg-secondary rounded-lg text-2xl" type="button" value="بحث">
            </div><!--./content-->

            <div class="logo w-78.75 mx-auto">
                <img src="../assets/imgs/logo.png" alt="logo">
            </div><!--./logo-->
        </div><!--./container-->
    </main>
</template>

<style scoped></style>