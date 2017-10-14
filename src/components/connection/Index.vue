<template>
  <section>
    <v-container grid-list-xl>
      <v-layout row wrap justify-center class="my-5">
        <company-info />
        <contect-me />
      </v-layout>
    </v-container>
  </section>
</template>
<script>
import ContectMe from './ContectMe'
import CompanyInfo from './CompanyInfo'
export default {
  components: {
    ContectMe, CompanyInfo
  }
}
</script>

