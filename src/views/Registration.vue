<template>
  <v-content class="pa-0">

    <v-container fluid class="pt-3 mb-0 grey lighten-5">
      <v-layout wrap align-center justify-center row fill-height class="my-0">
        <v-flex xs12 md10 class="my-0">
            <p class="google-font mb-0" style="font-size:200%;color:#0277bd">{{ChapterDetails.ChapterName}}'s Devfest 2019 Registration</p>
          <p class="google-font mt-0 mb-0" style="font-size:110%">Questions? Please contact <a href="mailto:info@gdgdang.org">{{ChapterDetails.ChapterEmail}}</a>.</p>
        </v-flex>
      </v-layout>
    </v-container>

    <v-container fluid class="grey lighten-3 mt-5 mb-5">
      <v-layout align-center justify-center>
        <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSfSKojRwVifinYdOSaU6B_ZetcFjwUIEkRsSb6O55Qbsb2Fyg/viewform?embedded=true" onload="this.style.height=this.contentDocument.body.scrollHeight +'px';" width= "90%" height="500rem" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>
      </v-layout>
    </v-container>

  </v-content>

</template>

<script>
import ChapterDetails from '@/assets/data/chapterDetails.json'
  export default {
    components: {
    },
    data() {
      return {
        ChapterDetails: ChapterDetails
      }
    },
  }
</script>
