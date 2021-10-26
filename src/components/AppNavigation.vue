<template>
    <span>
        <v-navigation-drawer
            app
            v-model="drawer"
            class="brown lighten-2"
            dark
            disable-resize-watcher
        >
            <v-list>
                <template v-for="(item, index) in items">
                    <v-list-title :key="index">
                        <v-list-title-content>
                            {{ item.title }}
                        </v-list-title-content>
                    </v-list-title>
                    <v-divider :key="`divider-${index}`"></v-divider>
                </template>
            </v-list>
        </v-navigation-drawer>
        <v-toolbar app color="brown darken-4" dark>
            <v-toolbar-side-icon
                class="hiddem-md-and-up"
                @click="drawer = !drawer"
            ></v-toolbar-side-icon>
            <v-spacer class="hidden-md-and-up"></v-spacer>
            <v-toolbar-title>{{ AppTitle }}</v-toolbar-title>
            <v-btn flat class="hidden-sm-and-down">Menú</v-btn>
            <v-spacer class="hidden-sm-and-down"></v-spacer>
            <v-btn flat class="hidden-sm-and-down">SIGN IN</v-btn>
            <v-btn color="brown lighten-3" class="hidden-sm-and-down"
                >JOIN</v-btn
            >
        </v-toolbar>
    </span>
</template>

<script>
export default {
    name: 'AppNavigation',
    data() {
        return {
            appTitle: 'Preparar comidita',
            drawer: false,
            items: [
                { title: 'Menú' },
                { title: 'Accede' },
                { title: 'Regístrate' },
            ],
        };
    },
};
</script>

<style scoped></style>
