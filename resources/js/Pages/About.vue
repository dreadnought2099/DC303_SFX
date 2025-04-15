<script setup>
import { Head } from "@inertiajs/vue3";
import PageLayout from "./PageLayout.vue";
</script>

<template>
    <Head title="About Page" />

    <PageLayout>
        <div
            class="bg-green-100 border border-green-300 p-8 rounded-lg w-[600px] mx-auto mt-12"
        >
            <div class="text-center">
                <p><strong>Name: </strong>Raymart E. Magallanes</p>
                <p><strong>Course & Year: </strong>BSIT 3</p>
                <p><strong>Cell No. : </strong>0950 665 3665</p>
            </div>
        </div>
    </PageLayout>
</template>
