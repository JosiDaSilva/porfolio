<template>
  <v-app-bar app color="black" dark flat class="px-12">
    <v-btn>
        <v-icon color="yellow" left class="mr-2">fas fa-signature</v-icon>Josiele da Silva
    </v-btn>
    <v-spacer></v-spacer>
    <v-btn text @click="scroll('inicio')" class="text-yellow">Inicio</v-btn>
    <v-btn text @click="scroll('about')" >Sobre Mí</v-btn>
    <v-btn text @click="scroll('portfolio')" >Proyectos</v-btn>
    <v-btn text @click="scroll('scontacto')" >Contacto</v-btn>
  </v-app-bar>
</template>
<script>
export default{

}
</script>
<style>

</style>