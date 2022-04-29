<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="12">
        <h1>{{message}}</h1>
        <h1>{{compMessage}}</h1>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
import {compMessage} from "@/state";

  export default {
    name: 'HelloWorld',
    setup() {
      return {compMessage}
    },
    data: () => ({
      message: "Hello Jos & Edgar"
    }),
  }
</script>
