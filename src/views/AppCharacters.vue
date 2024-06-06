<script>
import axios from 'axios';

export default {
    name: 'AppCharacters',
    data() {
        return {
            url_API: 'http://127.0.0.1:8000/',
            url_character: 'api/characters',
            characters: [],
            loading: true,
        }
    },
    methods: {
        callAPI(url) {
            axios
                .get(url)
                .then(response => {
                    // console.log(response)
                    this.characters = response.data.characters
                    this.loading = false
                })
        }
    },
    mounted() {
        const url = this.url_API + this.url_character
        this.callAPI(url);
    }
}



</script>

<template>
    <h1>Characters</h1>
</template>

<style></style>