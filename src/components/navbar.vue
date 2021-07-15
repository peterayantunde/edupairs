<template>
   <nav class="navbar navbar-expand-lg  navbar-light" style="background-color: #e3f2fd;">
  <div class="container">
     <a class="navbar-brand" href="#app">
      <b-img :src="require('../assets/img/logo.png')" width="200"></b-img>
      Edupairs
    </a>
    
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse justify-content-end" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#app">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#services">services</a>
        </li>
        
      </ul>
      
    </div>
  </div>
</nav>
</template>
<script>
export default {
  name: 'navbar',
    data(){
      return {
            
      }
    }
  }
</script>

