<template>
    <v-container fluid fill-height class="home-hero">
        <v-layout justify-center align-center column pa-5>
            <div class="display-4 font-weight-black white--text text-xs-center">
                COMIDITA SALUDABLE
            </div>
            <div
                class="
                    display-4
                    font-weight-black
                    white--text
                    text-xs-center
                    mb-3
                "
            >
                EN TU MESA
            </div>
            <div class="display-1 font-weight-bold white--text text-xs-center">
                Conviértete al fin en un cocinillas, con estos suculentos platos
                eleborados por los mejores chefs.
            </div>
            <v-btn fab class="mt-5 brown darken-4">
                <v-icon large color="white">expand_more</v-icon>
            </v-btn>
        </v-layout>
    </v-container>
</template>

<script>
export default {
    name: 'HomeHero',
};
</script>

<style scoped>
.home-hero {
    background: url('https://inlanderrestaurantweek.com/wp-content/uploads/2020/02/Fancy-plate-food-1024x576.jpg');
    background-size: cover;
    width: 100%;
    height: auto;
}
</style>
