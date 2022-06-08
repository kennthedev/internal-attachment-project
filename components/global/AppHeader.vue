<template>
  <div class="nav">
    <div class="top-container">
      <div class="logo"></div>

      <div class="search-container">
        <input
          type="text"
          class="space"
          placeholder="Search for events near you ....."
        />
        <button class="search space">search</button>
      </div>

      <div class="account-container">
        <a href="/login" class="login">Login</a>
        <a href="/signup" class="sign"> Sign up</a>
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
  height: 150px;
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
  padding: 0.7rem 2rem;
  border: 1px #2680EB  solid;
  border-radius: 0.3rem;
  color: #2680EB;
}
.search-container{
 
  padding-left: 4rem;
}
 
input{
  width:28rem;
  padding: 0.8rem 2rem;
   border-radius: 1.5rem;
   border: 2px rgb(170, 170, 170) solid;
   outline: none;
   font-family: 'Montserrat', sans-serif;

}

.search{
  padding: 0.7rem 2rem;
  border: none;
  border-radius: 1.5rem;
  background: #2680EB;
  color: white;
  width: 10rem;
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

.space{
  margin-left: 2rem;
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
  padding: 0.7rem 2rem;
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
  padding: 0.6rem 2rem;
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
  margin-top: -30px;
  width: 120px;
  height: 120px;
  background: url("~/assets/photos/mylogo.png");
  background-position: center;
  background-size: cover;
  cursor: pointer;
}

.second-nav{

  padding-left: 8rem;
}
</style>