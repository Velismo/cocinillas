<template>
    <v-container grid-list-lg>
        <v-layout row>
            <v-flex xs12 class="test-xs-center display-1 font-weight-black my-5"
                >¿Qué quieres hoy?</v-flex
            >
        </v-layout>
        <v-layout row wrap>
            <v-flex xs12 sm12 md4>
                <v-card>
                    <v-img
                        src="http://source.unsplash.com/hjCA3ecCXAQ"
                        height="500px"
                    >
                        <v-container fill-height fluid>
                            <v-layout fill-height>
                                <v-flex xs12 align-end flexbox>
                                    <span class="headline white--text"
                                        >PICOTÉO</span
                                    >
                                </v-flex>
                            </v-layout>
                        </v-container>
                    </v-img>

                    <v-card-title primary-title>
                        <h3 class="headline mb-0">Picoteo</h3>
                        <div>
                            Lorem ipsum dolor sit amet consectetur adipisicing
                            elit. Odit fugiat, accusantium consequuntur
                            quibusdam aliquam adipisci natus animi numquam
                            expedita totam similique repellendus asperiores
                            corporis doloribus perferendis sit aut non! Quo.
                        </div>
                    </v-card-title>
                </v-card>
            </v-flex>

            <v-flex xs12 sm12 md4>
                <v-card>
                    <v-img
                        src="http://source.unsplash.com/6S27S6pZ6o0"
                        height="500px"
                    >
                        <v-container fill-height fluid>
                            <v-layout fill-height>
                                <v-flex xs12 align-end flexbox>
                                    <span class="headline white--text"
                                        >SALADO</span
                                    >
                                </v-flex>
                            </v-layout>
                        </v-container>
                    </v-img>

                    <v-card-title primary-title>
                        <h3 class="headline mb-0">Salado</h3>
                        <div>
                            Lorem ipsum dolor sit amet consectetur adipisicing
                            elit. Odit fugiat, accusantium consequuntur
                            quibusdam aliquam adipisci natus animi numquam
                            expedita totam similique repellendus asperiores
                            corporis doloribus perferendis sit aut non! Quo.
                        </div>
                    </v-card-title>
                </v-card>
            </v-flex>

            <v-flex xs12 sm12 md4>
                <v-card>
                    <v-img
                        src="https://images.unsplash.com/photo-1563805042-7684c019e1cb?ixid=MnwxMjA3fDB8MHxzZWFyY2h8NHx8ZGVzc2VydHxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60"
                        height="500px"
                    >
                        <v-container fill-height fluid>
                            <v-layout fill-height>
                                <v-flex xs12 align-end flexbox>
                                    <span class="headline white--text"
                                        >DULCE</span
                                    >
                                </v-flex>
                            </v-layout>
                        </v-container>
                    </v-img>

                    <v-card-title primary-title>
                        <h3 class="headline mb-0">Dulce</h3>
                        <div>
                            Lorem ipsum dolor sit amet consectetur adipisicing
                            elit. Odit fugiat, accusantium consequuntur
                            quibusdam aliquam adipisci natus animi numquam
                            expedita totam similique repellendus asperiores
                            corporis doloribus perferendis sit aut non! Quo.
                        </div>
                    </v-card-title>
                </v-card>
            </v-flex>
        </v-layout>
    </v-container>
</template>

<script>
export default {
    name: 'HomePlans',
};
</script>

<style scoped></style>
