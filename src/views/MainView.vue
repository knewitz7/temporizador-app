<template>
  <nav> <!-- MENU DE NAVEGAÇÃO DO SITE --> </nav>
  <aside> <!-- Conteúdo secundário/lateral do site --> </aside>
  <main>
    <!-- Conteúdo pricipal do site -->

    <!-- 03. Utilizar o componente -->
    <MadCounter/>
  </main>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

// 01. Importar o arquivo do componente
import MadCounter from '@/components/MadCounter.vue';

export default defineComponent({
  name: 'MainView',

  // 02. Listar os componentes que serão utilizados
  components: {
    MadCounter
  },
});
</script>

<style scoped>

</style>