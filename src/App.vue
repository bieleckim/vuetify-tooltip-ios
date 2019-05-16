<template>
  <v-app>
    <v-tooltip max-width="85vw" bottom>
      <template #activator="{ on }">
        <v-btn class="mt-2 mb-1 mr-0" icon v-on="on">
          Hello
        </v-btn>
      </template>
      <span>World</span>
    </v-tooltip>
  </v-app>
</template>

<script>
export default {
  name: 'App',
  data () {
    return {
      //
    }
  }
}
</script>
