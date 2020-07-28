<template>
  <v-card>
    <!-- <v-img
        :src="cardContent.imgsrc"
      class="white--text align-end"
      gradient="to bottom, rgba(0,0,0,0.8), rgba(0,0,0,0.8)"
      :height="cardContent.detail.length*(56+7*4)+16+120"
    >-->
    <v-card-title class="headline">Education</v-card-title>
    <v-card-subtitle>Degree</v-card-subtitle>
    <!-- <v-card-text>
    </v-card-text> -->
    <CustomTextArea label="University" value="Technical University of Malaysia Malacca | Universiti Teknikal Malaysia Melaka (UTeM)" />
    <CustomTextArea label="Course" value="Study Bachelor of Computer Science (Artificial Intelligence), CGPA 3.69" />
    <CustomTextArea label="Core Subjects" value="Robotics, Machine Learning, Image Processing, Statistics, Calculus" />
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