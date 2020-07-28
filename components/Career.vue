<template>
  <v-card>
    <!-- <v-img
        :src="cardContent.imgsrc"
      class="white--text align-end"
      gradient="to bottom, rgba(0,0,0,0.8), rgba(0,0,0,0.8)"
      :height="cardContent.detail.length*(56+7*4)+16+120"
    >-->
    <v-card-title class="headline">Internship and Career</v-card-title>
    <v-card-subtitle>TopGlove</v-card-subtitle>
    <!-- <v-card-text>
    </v-card-text> -->
    <CustomTextArea label="Position" value="Data Scientist (Trainee)" />
    <CustomTextArea label="Job" value="Full-Stack Python Developer, Image Processing Project" />
    <CustomTextArea label="Core Skill" value="Python Programming, Neural Network, Machine Learning, Image Processing, Network Server" />
    <custom-text-area label="Experience" value="Full stack developer. Learnt many new things related to Business and Economics such as stock market and business skill." />
    <!-- </v-img> -->
  </v-card>
</template>

<script>
import CustomTextArea from '~/components/CustomTextArea.vue'
export default {
  components: {
    CustomTextArea,
  },
}
</script>