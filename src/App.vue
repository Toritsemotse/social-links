<template>
  <main>
    <div class="container"> 
      <div class="name-country-container">
        <div class="img-container"></div>
        <h2>Jessica Randall</h2>
        <p class="country">London, United Kingdom</p>
      </div>
      <p class="info">"Front-end developer and avid reader."</p>

      <div class="social">GitHub</div>
      <div class="social">Frontend Mentor</div>
      <div class="social">LinkedIn</div>
      <div class="social">Twitter</div>
      <div class="social">Instagram</div>
    </div>

  </main>
</template>

<style scoped>
  main{
    background-color: hsl(0, 0%, 8%);
    width: 100vw;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .container{
   width: 350px;
   height: 550px;
   background-color: hsl(0, 0%, 12%);
   border-radius: 10px;
   padding: 30px;

  }

  /* .name-country-container{
 
  } */

  .img-container{
    background-repeat: no-repeat;
    background-size: cover;
    background-image: url("/images/avatar-jessica.jpeg");
    width: 100px;
    height: 100px;
    border-radius: 50%; 
    margin-left: auto;
    margin-right: auto;
  }

  h2{
    text-align: center;
    color: hsl(0, 0%, 100%);
    margin-top: 20px;
    font-weight: 700;
  }

  p{
    text-align: center;
    font-weight: 400;
    margin-bottom:20px ;
  }

  .country{
    color: hsl(75, 94%, 57%);
    margin-bottom: 20px;
    font-weight: 600;
    font-size: 12px;
  }

  .info{
    font-size: 12px;
    font-weight: 600;
    color: hsl(0, 0%, 100%);
  }

  .social {
    width: 100%;
    height: 40px;
    background-color: hsl(0, 0%, 20%);
    margin-left: auto;
    margin-right: auto;
    border-radius: 7px;
    color: white;
    display: flex;
    align-items: center;
    justify-content: center;
    font-weight: 600;
    margin-top: 10px;
  }

  .social:hover{
    background-color: hsl(75, 94%, 57%);
    color: black;
  }
  
</style>