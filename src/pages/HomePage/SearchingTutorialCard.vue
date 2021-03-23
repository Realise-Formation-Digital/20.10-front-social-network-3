<template>
    <v-col sm="5" offset="1">
        <v-card 
          class="elevation-5"
          height="100%" 
        >
            <v-row class="d-flex justify-center">
              <v-card-title>
                Recherche de tutoriels
              </v-card-title>
              <v-card-subtitle>
              <v-form              >
                <v-text-field
                  label="Je veux apprendre à"
                ></v-text-field>

                <v-text-field
                    label="avec la technologie"
                    class="mt-n5"
                ></v-text-field>

                  <v-card-actions>
                    <v-btn color="primary" class="mb-8">
                    <v-icon left>mdi-text-box-search-outline</v-icon>
                      Lancer la recherche
                    </v-btn>
                  </v-card-actions>

                </v-form>
          </v-card-subtitle>
          </v-row>
        </v-card>
      </v-col>   
</template>

<script>
export default {
    name: 'SearchingTutorialCard'
}
</script>