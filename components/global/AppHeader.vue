<template>
  <div class="nav">
    <div class="top-container">
      <div class="logo"></div>

      <div class="search-container">
        <input
          type="text"
          class="space border-left"
          placeholder="Search for events near you ....."
        />
        <button class="search">search</button>
      </div>

      <div class="account-container">
        <nuxt-link to="/login" class="login">Login</nuxt-link>
        <nuxt-Link to="/signup" class="sign">Sign up</nuxt-Link>
      </div>
    </div>

    <div class="second-nav">
      <ul>
        <li><a href="" class="active">Home</a></li>
        <li><a href="">Music</a></li>
        <li><a href="">Art</a></li>
        <li><a href="">Expo</a></li>
        <li><a href="">Tech</a></li>
      </ul>
    </div>
  </div>
</template>


<style scoped>


.nav{
  width: 100%;
  height: 100px;
  background: rgb(255, 255, 255);
  padding-top: 1.5rem;
  font-family: 'Oswald', sans-serif;
  box-shadow: rgb(124, 124, 124) 0 2px 16px  ;
  position: fixed;
  top: 0;
  z-index: 1;
  
}

.account-container{
  padding-top: 0.5rem;
}

.active{
  padding: 0.3rem 1rem;
  border: 1px #2680EB  solid;
  border-radius: 0.3rem;
  color: #2680EB;
}
.search-container{
 
  padding-left: 4rem;
}
 
input{
  width:28rem;
  padding: 0.5rem 0.8rem;
   border: 1px rgb(170, 170, 170) solid;
   outline: none;
   font-family: 'Montserrat', sans-serif;
   border-radius: 1.5rem;
 
}

.search{
  padding: 0.4rem 0.5rem;
   border:none;
  border-radius: 1.5rem;
  margin-left: 1rem;
  background: #2680EB;
  color: white;
  width: 6rem;
  font-size: 1rem;
    font-weight: 500;
    cursor: pointer;
  font-family: 'Oswald', sans-serif;
}

.top-container{
  width:100%;
  display: flex;
  justify-content: space-around;
}



li{
  list-style: none;
  display: inline-block;

}
a{
  text-decoration: none;
  margin-left:4rem ;
  font-family: 'Oswald', sans-serif;
  color: rgb(112, 112, 112);
}


.sign{
  padding: 0.5rem 1rem;
  border: none;
  color: white;
  background: #C80962;
  margin-right: 2rem;
  border-radius: 0.4rem;
  font-family: 'Oswald', sans-serif;
  font-size: 1rem;
  cursor: pointer;
  font-weight: 500;
}

.login{
  padding: 0.4rem 1.5rem;
  background: none;
  border: 2px #2680EB solid;
  color: #2680EB;
  margin-right: 2rem;
  border-radius: 0.4rem;
  font-family: 'Oswald', sans-serif;
  font-size: 1rem;
  cursor: pointer;
  font-weight: 500;
}


.logo{
  margin-top: -20px;
  width: 80px;
  height: 80px;
  background: url("~/assets/photos/mylogo.png");
  background-position: center;
  background-size: cover;
  cursor: pointer;
}

.second-nav{
margin-top: -0.8rem;
  padding-left:12rem;
}
</style>