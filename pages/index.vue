<template>
    <div class="w-full px-2">
        <ListItem>
            João da Silva
            <template #actions>
                <button class="px-2 py-1 bg-green-500 text-white rounded">Editar</button>
                <button class="px-2 py-1 bg-red-500 text-white rounded">Excluir</button>
            </template>
        </ListItem>

        <button class="w-full p-4 mt-8 border border-blue-200 rounded bg-blue-500 text-white flex items-center justify-center">
            Adicionar Contato
        </button>
    </div>
</template>

<script setup>
import ListItem from './ListItem.vue';
</script>
