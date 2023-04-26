<template >
    <div class="contact">
        <div class="contact-box">
    <div class="contact-links">
      <h4>CONTACT ME</h4>
      <div class="links">
        <div class="link">
          <a><i class="fa-brands fa-linkedin fa-2xl" style="color: #0d0d0d;"></i></a>
        </div>
        <div class="link">
          <a><i class="fa-brands fa-twitter fa-2xl" style="color: #0d0d0d;"></i></a>
        </div>
        <div class="link">
          <a></a>
        </div>
        <div class="link">
          <a></a>
        </div>
      </div>
    </div>
    <div class="contact-form-wrapper">
      <form  action="https://formspree.io/f/xvononpq"
  method="POST">
        <div class="form-item">
          <input type="text" name="name" required>
          <label>Name:</label>
        </div>
        <div class="form-item">
          <input type="text" name="email" required>
          <label>Email:</label>
        </div>
        <div class="form-item">
          <textarea class="" name="message" required></textarea>
          <label>Message:</label>
        </div>
        <button class="submit-btn">Send</button>  
      </form>
    </div>
  </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .contact{
        padding-top:6rem;
        min-height:100vh;
        align-items: center;
        padding-left: 11rem;
    }
    #contact {
  background-color: #6a9ac4;
  display: flex;
  justify-content: center;
  align-items: center;
}

.contact-box {
  width: clamp(100px, 90%, 1000px);
  margin: 80px 50px;
  display: flex;
  flex-wrap: wrap;
}

.contact-links, .contact-form-wrapper {
  width: 50%;
  padding: 8% 5% 10% 5%;
}


.contact-links {
  background-color: #601a54;
  background:
    radial-gradient(
      circle at 55% 92%, #a06e98 0 12%, transparent 12.2%
    ), 
    radial-gradient(
      circle at 94% 72%, #9f7ca5 0 10%, transparent 10.2%
    ), 
    radial-gradient(
      circle at 20% max(78%, 350px),  #8c7890 0 7%, transparent 7.2%
    ), 
    radial-gradient(
      circle at 0% 0%,  #93509f 0 40%, transparent 40.2%
    ), 
    #dba8e6;
  border-radius: 10px 0 0 10px;
}

.contact-form-wrapper {
  background-color: #ffffff8f;
  border-radius: 0 10px 10px 0;
}

@media only screen and (max-width: 800px) {
  .contact-links, .contact-form-wrapper {
    width: 100%;
  }
  
  .contact-links {
    border-radius: 10px 10px 0 0;
  }
  
  .contact-form-wrapper {
    border-radius: 0 0 10px 10px;
  }
}

@media only screen and (max-width: 400px) {
  .contact-box {
    width: 95%;
    margin: 8% 5%;
  }
}

h4 {
  color: #fff;
  letter-spacing: 2px;
  text-align: center;
  transform: scale(.95, 1);
}

.links {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  padding-top: 50px;
}

.link {
  margin: 10px;
  cursor: pointer;
}
.form-item {
  position: relative;
}

label, input, textarea {
  font-family: 'Poppins', sans-serif;
}

label {
  position: absolute;
  top: 10px;
  left: 2%;
  color: #999;
  font-size: clamp(14px, 1.5vw, 18px);
  pointer-events: none;
  user-select: none;
}

input, textarea {
  width: 100%;
  outline: 0;
  border: 1px solid #ccc;
  border-radius: 4px;
  margin-bottom: 20px;
  padding: 12px;
  font-size: clamp(15px, 1.5vw, 18px);
}

input:focus+label, 
input:valid+label, 
textarea:focus+label, 
textarea:valid+label {
  font-size: clamp(13px, 1.3vw, 16px);
  color: #777;
  top: -20px;
  transition: all .225s ease;
}

.submit-btn {
  background-color: #f47efd;
  filter: drop-shadow(2px 2px 3px #0003);
  color: #fff;
  font-family: "Poppins",sans-serif;
  font-size: clamp(16px, 1.6vw, 18px);
  display: block;
  padding: 12px 20px;
  margin: 2px auto;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  user-select: none;
  transition: 0.2s;
}

.submit-btn:hover {
  transform: scale(1.1, 1.1);
}

.submit-btn:active {
  transform: scale(1.1, 1.1);
  filter: sepia(0.5);
}

@media only screen and (max-width: 800px) {
  h4 {
    font-size: clamp(40px, 10vw, 60px);
  }
}

@media only screen and (max-width: 400px) {
  h4 {
    font-size: clamp(30px, 12vw, 60px);
  }
  
  .links {
    padding-top: 30px;
  }
  
  img {
    width: 38px;
    height: 38px;
  }
}

</style>