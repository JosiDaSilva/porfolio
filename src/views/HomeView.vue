<template>
 <v-app id="home">
<NavBar/>
<v-container fluid>
<div class="head">
<v-row>
  <v-col cols="5">
    <div style="position: relative" class="mt-16">
    <h1 class="text-grey">Hola,</h1>
    <h1 class="text-grey">Soy Josiele</h1>
    <span class="text-grey">Web Designer & Developer</span>
    <v-btn tile dark class="text-yellow mt-8" variant="outlined">Contáctame</v-btn>
    </div>
  </v-col>
  <v-col cols="7"></v-col>
</v-row>
</div>
</v-container>

 </v-app>
</template>

<script>
import { defineComponent } from 'vue';

// Components
import NavBar from '@/components/NavBar.vue';

export default defineComponent({
  name: 'HomeView',

  components: {
    NavBar
  },
});
</script>
<style scoped>
.v-container{
  padding: 16px 0;
}

.head{
 position: relative;
 text-align: center; 
 padding: 12px;
 margin-bottom: 6px;
 height: 400px;
 width: 100%;
 color: white;
}
.head:before{
  content: " ";
  position: absolute;
  top: 0;
  left:0;
  height: 100%;
  width: 50%;
  background: black;
  transform: skew(0deg, 6deg);
}

.head:after{
  content: " ";
  position: absolute;
  top: 0;
  right:0;
  height: 100%;
  width: 50%;
  background: black;
  transform: skew(0deg, -6deg);
}

</style>