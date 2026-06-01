<script setup>
import Card from '@/components/cards/Card.vue';
import Table from '@/components/tables/Table.vue';
import customers from '@/assets/database/customers.json'

</script>

<template>
    <main class="w-full pt-17.5">
        <div class="container mx-auto">
            <Card />
            <Table />
        </div><!--./conainer-->
    </main>
</template>

<style scoped></style>