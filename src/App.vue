<script>
import MenuLateral from "@/components/MenuLateral.vue";
import cabecalho_principal from "@/components/cabecalho_principal.vue";
import principal_content from "@/components/principal_content.vue";
import rodape_principal from "@/components/rodape_principal.vue";
export default {
  components: {
    MenuLateral,
    cabecalho_principal,
    principal_content,
    rodape_principal,
  },
};
</script>
<template>
  <MenuLateral />
  <cabecalho_principal />
  <principal_content />
  <rodape_principal />
</template>
<style></style>
