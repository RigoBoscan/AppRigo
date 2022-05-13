<template>
  <v-container class="container" grid-list-md>
    <v-layout row wrap>
      <v-flex lg3 xs12>
        <v-card class="card">
          <v-img src="./images/Propidad.svg">
            <v-container>
              <div class="entrega">
                <h4>Entrega inmediata</h4>
              </div>
            </v-container>
          </v-img>

          <v-container>
            <div class="proyect-title">
              <h2>Nombre del proyecto</h2>
              <v-btn icon>
                <img src="./icons/favorite.svg" alt="" />
              </v-btn>
            </div>

            <div class="location">
              <p>Barrio, Ciudad</p>
            </div>

            <div class="indications">
              <p class="indication_room">
                <img src="./icons/Room.svg" alt="" /> 1 a 2
              </p>
              <p class="indication_bath">
                <img src="./icons/Bath.svg" alt="" /> 1
              </p>
              <p class="indication_meters">
                <img src="./icons/Meters.svg" alt="" /> 40.2 m2
              </p>
              <p class="indication_garage">
                <img src="./icons/Garage.svg" alt="" /> Incluido
              </p>
            </div>

            <span class="proyect_price">
              <div>
                <p class="proyect_price-currency">
                  Precios desde (COP) <br />
                  <b>$0.000</b> a <b>$0.000</b> millones
                </p>
              </div>
            </span>

            <v-card-action> </v-card-action>
          </v-container>
        </v-card>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<style lang="scss" scoped>
@import "./scss/MainApp.scss";
</style>

<script>
export default {
  name: "MainApp",
};
</script>
