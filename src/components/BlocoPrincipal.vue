<script>
import NovoBloco from "@/components/BloCo.vue";
export default {
  components: { NovoBloco },
  data() {
    return {
      bosses: [
        {
          titulo: "Iudex Gundyr",
           imagem: new URL("./imgs/1.jpg", import.meta.url).href,
        },
        {
          titulo: "Vordt do vale Boreal",
          imagem: new URL("./imgs/2.jpg", import.meta.url).href,
        },
        {
          titulo: "Grande Árvore Apodrecida",
          imagem: new URL("./imgs/3.jpg", import.meta.url).href,
        },
        {
          titulo: "Sábio de Cristal",
          imagem: new URL("./imgs/4.jpg", import.meta.url).href,
        },
        {
          titulo: "Vigilantes do Abismo",
          imagem: new URL("./imgs/5.jpg", import.meta.url).href,
        },
        {
          titulo: "Diáconos das Profundezas",
          imagem: new URL("./imgs/6.jpg", import.meta.url).href,
        },
        {
          titulo: "Alto Lorde Wolnir",
          imagem: new URL("./imgs/7.jpg", import.meta.url).href,
        },
        {
          titulo: "Antigo Rei Demonio",
          imagem: new URL("./imgs/8.jpg", import.meta.url).href,
        },
        {
          titulo: "Pontifice Sulyvan",
          imagem: new URL("./imgs/9.jpg", import.meta.url).href,
        },
        {
          titulo: "Yhorm, O Gigante",
          imagem: new URL("./imgs/10.jpg", import.meta.url).href,
        },
        {
          titulo: "Aldrich, O devorador de Deuses",
          imagem: new URL("./imgs/11.jpg", import.meta.url).href,
        },
        {
          titulo: "Dançarina do Vale Boreal",
          imagem: new URL("./imgs/12.jpg", import.meta.url).href,
        },
        {
          titulo: "Armadura do Matador de Dragões",
          imagem: new URL("./imgs/13.jpg", import.meta.url).href,
        },
        {
          titulo: "Oceiros, O Rei Consumido",
          imagem: new URL("./imgs/14.jpg", import.meta.url).href,
        },
        {
          titulo: "Campeão Gundyr",
          imagem: new URL("./imgs/15.jpg", import.meta.url).href,
        },
        {
          titulo: "Lothric/Lorian, O Pincipe Mais Novo",
          imagem: new URL("./imgs/16.jpg", import.meta.url).href,
        },
        {
          titulo: "Wyvern Ancião",
          imagem: new URL("./imgs/17.jpg", import.meta.url).href,
        },
        {
          titulo: "Rei da Tempestade/Rei Sem Nome",
          imagem: new URL("./imgs/18.jpg", import.meta.url).href,
        },
        {
          titulo: "Alma das Cinzas",
          imagem: new URL("./imgs/20.jpg", import.meta.url).href,
        },
        {
          titulo: "Guardião do Túmulo do Campeão",
          imagem: new URL("./imgs/21.jpg", import.meta.url).href,
        },
        {
          titulo: "Irmã Fried",
          imagem: new URL("./imgs/22.jpg", import.meta.url).href,
        },
        {
          titulo: "Príncipe Demônio",
          imagem: new URL("./imgs/25.jpg", import.meta.url).href,
        },
        {
          titulo: "Midir, Devorador da Escuridão",
          imagem: new URL("./imgs/27.jpg", import.meta.url).href,
        },
        {
          titulo: "Guardião do Túmulo do Campeão",
          imagem: new URL("./imgs/28.jpg", import.meta.url).href,
        },
        {
          titulo: "Cavaleiro Escravo Gael",
          imagem: new URL("./imgs/29.jpg", import.meta.url).href,
        },
      ],
    };
  },
};
</script>
<template>
    <div class="boss">
      <NovoBloco
        v-for="(boss, i) of bosses"
        :key="i"
        :titulo="boss.titulo"
        :imagem="boss.imagem"
      />
    </div>
</template>
<style>
</style>
