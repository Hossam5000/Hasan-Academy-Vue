<script setup>
import customers from '@/assets/database/customers.json'

const props = defineProps(
    {
        customer: { type: Object },
    },
)

const targetPhone = '01550285256';


</script>

<template>
    <div class="overflow-x-auto my-6 px-4">
        <table class="min-w-full table-auto border-collapse rounded-lg overflow-hidden ">

            <!-- Table Head -->
            <thead class="bg-blue text-white text-left">
                <tr>
                    <th class="px-4 py-3 text-sm font-semibold">اليوم</th>
                    <th class="px-4 py-3 text-sm font-semibold">الساعة</th>
                </tr>
            </thead>

            <!-- Table Body -->
            <tbody class="text-left text-gray-700 bg-white">

                <!-- first row -->
                <tr class="border-b hover:bg-gray-50">
                    <td class="px-4 py-3 text-sm">الاحد</td>
                    <td class="px-4 py-3 text-sm font-bold text-blue">02:30 PM</td>
                </tr>
                <!-- second row -->
                <tr class="">
                    <td class="px-4 py-3 text-sm">الاربعاء</td>
                    <td class="px-4 py-3 text-sm font-bold text-blue">05:00 PM</td>
                </tr>
            </tbody>
        </table>
    </div>
</template>



<style scoped></style>