<template>
    <div class="testimonials">
      
    </div>
</template>
<script>

export default {
    
}
</script>
<style scoped>
.testimonials{
    padding-top:6rem;
    min-height:100vh;
}
.carousel-caption button{
  transition: all 0.25s ease 0s;
 
}
.carousel-caption button:hover{
  scale: 1.05;
  box-shadow: 5px 5px 5px #000;
}
.carousel-item{
  position: relative;
  height: 100%;
}
.carousel-item img{
  height: 650px;
  
}
#carouselCategory{
  width: 100%;
  min-width: 300px;
  /* height: 600px; */
  margin: 0 auto;
  background-color:transparent;
}
.carousel-caption{
  position: absolute;
  top: 30%;
  bottom: 30%;
  background-color: #2a2a2ac2;
  display: flex;
  flex-flow: column nowrap;
  justify-content: space-around;
  align-items: center;
}

.carousel-item p{
  color: #ffffff;
}
    
</style>