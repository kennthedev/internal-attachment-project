

<template>
  <div class="back">
    <nuxt-link to="/"
      ><div class="logo">
        <img src="~/assets/photos/logo2.png" alt="" class="log" /></div
    ></nuxt-link>

    <div class="form-container">
      <h2>Create an account</h2>
      <form action="">
        <div>
          <legend>Name</legend>
          <input type="text" required />
        </div>

        <div class="inputs">
          <legend>Email</legend>
          <input type="Email" required />
        </div>

        <div>
          <legend>Password</legend>
          <input type="text" required />
        </div>
      </form>
      <div class="btn-container">
        <button class="btn-sign">Sign Up</button>
      </div>

      <div class="signin">
        <p>Already have an account?</p>
        <a href="">Sign in</a>
      </div>
    </div>
  </div>
</template>

<style scoped>

.log{
width: 100%;
height: 100%;
}


.logo{
   width: 80px;
  height: 90px;
  margin-top: 1rem;
  margin-left: 3rem;
  cursor: pointer;
}


.form-container {
  max-width: 28rem;
  background: rgba(255, 255, 255, 0.541);
  padding-top: 1rem;
  padding-bottom: 2rem;
  margin-inline: auto;
  position: relative;
  z-index: 2;
  border-radius: 1rem;
  
  margin-top: 1rem;
}
.signin {
  text-align: center;
  padding-top: 2rem;
}
form {
  width: 100%;
  padding: 2rem;
}
h2 {
  text-align: center;
  font-size: 2rem;
  color: #4b494a;
}

.btn-container{
  width: 100%;
  text-align: center;
 
}
.btn-sign {
  width: 80%;
  padding: 1rem 3rem;
  border: none;
  border-radius: 0.5rem;
  color: white;
  font-family: "Oswald", sans-serif;
  font-size: 1rem;
  font-weight: 500;
  cursor: pointer;
  background-color: #c80962;
}

legend {
  margin-bottom: 1rem;
  font-size: 1.2rem;
}

input:focus {
  border-bottom: #c80962 solid 2px;
}

input {
  outline: none;
  border: none;
  background: none;
  border-bottom: 2px solid rgb(97, 97, 97);
  width: 70%;
  margin-bottom: 2rem;
}

.inputs {
  width: 100%;
}

.back {
  width: 100%;
 padding-bottom: 6rem;
  position: relative;
  margin: 0 auto;
  overflow-y: hidden;
  background: url("~/assets/photos/myimage.jpg");
  background-size: cover;
  background-position: bottom;
  background-repeat: no-repeat;
  font-family: "Oswald", sans-serif;
}

template::-webkit-scrollbar {
  display: hidden;
}
</style>



