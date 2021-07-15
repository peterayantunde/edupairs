<template>
  <b-container class="services" type="dark" variant="info">
    <b-row class="services" >
      <h2 class="services-head" style="text-align: center">Our Services</h2>
      <b-col sm="6" class="tutor">
        <h2>Hire a Tutor</h2>
        <b-img :src="require('../assets/img/teacher.jpg')" width="200"></b-img><br><br>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Earum asperiores quisquam similique. Rem, at quia.</p>
      </b-col>
      <b-col sm="6" class="pquestion">
        <h2>Get Our Past Question</h2>
        <b-img :src="require('../assets/img/pqs.png')" width="200"></b-img><br><br>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium impedit deserunt aut recusandae sunt labore?</p>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
export default {
  name: 'servicess',
    data(){
      return {
            
      }
    }
  }
</script>
