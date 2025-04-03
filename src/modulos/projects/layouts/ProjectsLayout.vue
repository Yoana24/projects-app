
<template>

<MenuSup></MenuSup>


    <main>
         
        <MenuLateral></MenuLateral>
        <RouterView></RouterView>
    </main>
</template>

<script lang="ts" setup>

import MenuSup from '@/modulos/comun/components/MenuSup.vue';
import MenuLateral from '../components/MenuLateral.vue';


</script>