<template>
    <v-container fluid>
        <v-card>
            <v-row class="justify-center">
                <v-col cols="4">
                    <v-card>
                        <v-card-title class="text-h3 text-center pa-2">Algo de mi como desarrollador</v-card-title>
                        <v-card-text>
                            <p class="text-center text-h5">Conocimientos en mi área</p>
                            <div class="text-justify text--primary">
                                Mi experienza como desarrollador comenzo en Poder Judicial en el Estado de Puebla, comenzando con algunas tecnologias
                                como Java, despues el tecnologias de desarrollo web, utilizando en el frontend VueJs y en backend Laravel.
                            </div>
                        </v-card-text>
                        <v-card-actions>
                        <v-btn
                            variant="text"
                            color="teal-accent-4"
                        >
                            VER MÁS
                        </v-btn>
                        </v-card-actions>
                    </v-card>
                </v-col>
            </v-row>
            <v-row dense class="pa-4">
                <v-col cols="4">
                    <v-card>
                        <v-img
                        src="https://cdn.vuetifyjs.com/images/cards/house.jpg"
                        class="white--text align-end"
                        gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
                        height="200px"
                        cover
                        >
                            <v-card-title class="text-white">
                                Proyecto para hacer preguntas por usuario
                                utilizando LARAVEL, VUEJS Y MYSQL
                                <v-card-actions>
                                    <v-btn
                                        class="ml-2"
                                        color="#fffff"
                                        variant="outlined"
                                        size="small"
                                    >
                                        ver más 
                                    </v-btn>
                                </v-card-actions>
                            </v-card-title>
                        </v-img>
                    </v-card>
                </v-col>
                <v-col cols="4">
                    <v-card>
                        <v-img
                        src="https://cdn.vuetifyjs.com/images/cards/road.jpg"
                        class="white--text align-end"
                        gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
                        height="200px"
                        cover
                        >
                        <v-card-title class="text-white"></v-card-title>
                        </v-img>
                    </v-card>
                </v-col>
                <v-col cols="4">
                    <v-card>
                        <v-img
                        src="https://cdn.vuetifyjs.com/images/cards/plane.jpg"
                        class="white--text align-end"
                        gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
                        height="200px"
                        cover
                        >
                        <v-card-title class="text-white"></v-card-title>
                        </v-img>
                    </v-card>
                </v-col>
            </v-row>
        </v-card>
    </v-container>
</template>

<script>
export default {
    name: 'YoApp',
    data() {
        return {
            show: false,
        }
    }
}
</script>

<style>

</style>