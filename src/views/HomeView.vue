<template>
  <v-container fill-height fluid>
    <v-container>
      <v-row>
        <v-col class="text--secondary" cols="6">
          <h2 class="h2">Pet's Donation</h2>
          <body1>A proposta do nosso projeto é a criação de uma plataforma voltada à adoção de animais domésticos.</body1>
          <br><br>
          <body1>Com o desenvolvimento deste site visamos proporcionar acessibilidade à adoção de animais de forma prática e segura para ambos os lados.</body1>
          <br><br>
          <v-btn color="indigo lighten-3" @click="faleconosco">Fale Conosco</v-btn>
        </v-col>
                  
        <v-col cols="auto">
          <v-img max-height="300" max-width="400" src="@/assets/images/pets_logo.png"></v-img>  
        </v-col>
      </v-row>
      <v-row>
        <v-col class="text--secondary" cols="auto">
          <br><br>
          <v-img max-height="200" max-width="200" src="https://t1.ea.ltmcdn.com/pt/razas/5/3/7/vira-lata-caramelo_735_0_600.jpg"></v-img>
          <br>
          <v-btn color="indigo lighten-3" @click="cachorros">Cachorros</v-btn>
        </v-col>
        <v-col class="text--secondary" cols="auto">
          <br><br>
          <v-img max-height="188" max-width="225" src="https://www.petz.com.br/blog/wp-content/uploads/2021/11/enxoval-para-gato-Copia.jpg"></v-img>
          <br>
          <v-btn color="indigo lighten-3" @click="gatos">Gatos</v-btn>
        </v-col>
        <v-col class="text--secondary" cols="auto">
          <br><br>
          <v-img max-height="188" max-width="205" src="https://www.petz.com.br/blog/wp-content/uploads/2020/07/adocao-de-coelho.jpg"></v-img>
          <br>
          <v-btn color="indigo lighten-3" @click="coelhos">Coelhos</v-btn>
        </v-col>
        <v-col class="text--secondary" cols="auto">
          <br><br>
          <v-img max-height="188" max-width="187" src="https://ivensmiranda.files.wordpress.com/2016/11/cd-canto-campainha-canario-belga-original-p-aves-em-gaiola-15814-mlb20109008167_062014-f.jpg"></v-img>
          <br>
          <v-btn color="indigo lighten-3" @click="passaros">Passaros</v-btn>
        </v-col>
        <v-col class="text--secondary" cols="auto">
          <br><br>
          <v-img max-height="188" max-width="188" src="https://t2.uc.ltmcdn.com/pt/posts/1/6/2/como_saber_se_minha_tartaruga_esta_hibernando_16261_600.jpg"></v-img>
          <br>
          <v-btn color="indigo lighten-3" @click="outros">Outros Animais</v-btn>
        </v-col>
      </v-row>
    </v-container>
  </v-container>
</template>

<script>
export default{
  methods: {
    faleconosco() {
      this.$router.push({ name: "Fale Conosco"});
    },
    cachorros() {
      this.$router.push({ name: "Cachorros"});
    },
    gatos() {
      this.$router.push({ name: "Gatos"});
    },
    coelhos() {
      this.$router.push({ name: "Coelhos"});
    },
    passaros() {
      this.$router.push({ name: "Passaros"});
    },
    outros() {
      this.$router.push({ name: "Outros"});
    }
  }
};
</script>

<style>

</style>