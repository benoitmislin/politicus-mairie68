<template>
    <main>
        <h1>{{ contents.titre }}</h1>
        <nuxt-img src="../public/img/image.png" />
        <ul>
            <li v-for="item in contents" :key="item.id">
                {{ item.titre }}
            </li>
        </ul>
    </main>
</template>

<script setup>

    var titre = "Coucou";

    var contents = [{
        'titre' : 'Coucou',
        'texte' : 'Lorem'
    },
    {
        'titre' : 'Zob',
        'texte' : 'Lorem'
    }]
    

</script>

<style lang="scss" scoped>

</style>