<template>
  <v-container>
    <v-row justify="center">
      <v-col cols="6">
        <v-card>
          <v-card-title>ランキングページ</v-card-title>
        </v-card>
      </v-col>
    </v-row>
      <v-btn
      
      color="pink"
      elevation="30"
      x-large
    >
      1位
    </v-btn>
       <v-btn
      
      color="pink"
      elevation="30"
      x-large
    >
      2位
    </v-btn>
       <v-btn
      
      color="pink"
      elevation="30"
      x-large
    >
      3位
    </v-btn>   <v-btn
      
      color="pink"
      elevation="30"
      x-large
    >
      4位
    </v-btn>
    

    <template>
  <div class="text-center">
    <v-rating
      v-model="rating"
      background-color="purple lighten-3"
      color="purple"
      large
    ></v-rating>
    <v-rating
      v-model="rating"
      background-color="pink lighten-3"
      color="pink"
      large
    ></v-rating>
    <v-rating
      v-model="rating"
      background-color="orange lighten-3"
      color="orange"
      large
    ></v-rating>
    <v-rating
      v-model="rating"
      background-color="green lighten-3"
      color="green"
      large
    ></v-rating>
    <v-rating
      v-model="rating"
      background-color="red lighten-3"
      color="red"
      large
    ></v-rating>
    <v-rating
      v-model="rating"
      background-color="indigo lighten-3"
      color="indigo"
      large
    ></v-rating>
  </div>
</template>

  </v-container>
</template>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>