<template>
    <div class="">
        pokemon: {{ pokemon }}
    </div>
</template>

<script setup>
import { getPokemonURL } from '@/api/pokemon'

const pokemon = ref('')

console.log(getPokemonURL())

const res = await useFetch(getPokemonURL())

pokemon.value = res.data._rawValue.name

</script>