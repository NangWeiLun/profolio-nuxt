<template>
  <v-card>
    <!-- <v-img
        :src="cardContent.imgsrc"
      class="white--text align-end"
      gradient="to bottom, rgba(0,0,0,0.8), rgba(0,0,0,0.8)"
      :height="cardContent.detail.length*(56+7*4)+16+120"
    >-->
    <v-card-title class="headline">Some Project and Skill</v-card-title>
    <v-card-subtitle>
      I learnt many computer languages in the field of Software, Web, Database.
      These projects/assignments were done on the course.
    </v-card-subtitle>
    <!-- <v-card-text>
    </v-card-text>-->
    <CustomTextArea
      label="Final Year Project, Replication of LipNet model Using Tensorflow Library and Python"
      value="-	A software that use a camera to perform lipreading to know what a person talking without input of sound. This project is to research and review on LipNet model. This software is to help people communicate in noisy environment. And, this project builds new dataset for train and test.
-	Written in Python. Built with Ubuntu, OpenCV, Nvidia GEFORCE 940M, Keras API."
    />
    <CustomTextArea
      label="Workshop 2, Intelligent Farming Robot Prototype Using IoT Application"
      value="-	A robot with arm and camera that can auto plant and harvest crop. A farm used vertical farming method with the help of robot.
-	Written in Python. Built with ev3dev (Debian) + SSH + SMBus, OpenCV, Lego Mindstorm EV3, TETRIX, HiTechnic, Google Cloud's Vision API."
    />
    <CustomTextArea
      label="Workshop 1, Online Police Reporting System"
      value="-	A system that help police store report data, share to all police station and analysis cases. This system also lets residents to do police report without going to police station.
-	Written in C++, SQL. Built with QT Quick 2 and MySQL."
    />
    <CustomTextArea
      label="Evolutionary Computing Project, Employee Assignation For A Project By Using Genetic Algorithm"
      value="-	A software with genetic algorithm implemented to achieve the best solution which pay out the minimum of salary and get back the maximum of employees’ efficiency.
-	Written in C++."
    />
    <CustomTextArea
      label="Object Oriented Programming Project, Smartphone Inventory System"
      value="-	A system to help calculate price, store record in database, and ensure transaction runs efficiently.
-	Written in Java, SQL. Built with Apache Derby."
    />
    <CustomTextArea
      label="Other Skill"
      value="Programming Language: R, Python (PyTorch, Pandas), MATLAB, PHP, Vuejs, HTML, JS, CSS. 
    Event Planning 25%, Communication 50%, Leadership 50%, Creativity 75%, Computer 100%
    "
    />
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