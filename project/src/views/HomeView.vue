<script setup>
    import Navbar from '@/components/Navbar.vue';
    import Hero from '@/components/Hero.vue';
    import HomeCards from '@/components/HomeCards.vue';
    import JobListings from '@/components/JobListings.vue';
</script>

<template>
    <section>
        <Hero title="Become a Vue Dev" subtitle="Find the Vue job that fits your skills and needs"/>
        <HomeCards/>
        <JobListings :limit="3" showButton="true"/>
        <div class="m-auto max-w-lg my-10 px-6">
            <RouterLink
            to="/jobs"
            class="block bg-black text-white text-center py-4 px-6 rounded-xl hover:bg-gray-700"
            >View All Jobs</RouterLink
            >
        </div>
    </section>
</template>