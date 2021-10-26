<template>
    <span>
        <home-hero></home-hero>
    </span>
</template>

<script>
import HomeHero from '@/components/HomeHero';
// @ is an alias to /src
export default {
    name: 'Home',
    components: {
        HomeHero,
    }
};
</script>
