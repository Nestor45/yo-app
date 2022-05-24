<template>
    <div>
        <v-app-bar
            image="https://picsum.photos/1920/1080?random"
            dark
            prominent
        >
            <template v-slot:image>
                <v-img
                    gradient="to top right, rgba(19,84,122,.8), rgba(128,208,199,.8)"
                ></v-img>
            </template>
            <v-btn @click.stop="drawer = !drawer" size="x-large">
                <v-icon >mdi-emoticon-cool-outline</v-icon>
                <p class="font-weight-black"> Yo_{ {{nombre}} } </p>
            </v-btn>
            <v-spacer></v-spacer>
            <v-btn icon>
                <v-icon>mdi-github</v-icon>
            </v-btn>
            <v-btn icon>
                <v-icon>mdi-twitter</v-icon>
            </v-btn>
            <v-btn icon>
                <v-icon>mdi-instagram</v-icon>
            </v-btn>
        </v-app-bar>
        <v-navigation-drawer v-model="drawer" temporary>
            <v-list density="compact" nav>
                <v-list-item prepend-icon="mdi-briefcase-variant-outline" title="Home" value="home"></v-list-item>
                <v-list-item prepend-icon="mdi-card-account-details-star" title="About" value="about"></v-list-item>
            </v-list>
        </v-navigation-drawer>
        
    </div>
</template>

<script>
    
export default {
    name:'HeaderApp',
    data: () => ({
        nombre: 'Click me',
        drawer: null,
    })
}
</script>

<style>

</style>