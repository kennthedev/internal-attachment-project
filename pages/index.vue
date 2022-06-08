



<template>
  <div class="home">
    <GlobalAppHeader />
    <div class="slider"></div>

    <div class="post1">
      <GlobalEventPost />
    </div>

    <slot />
  </div>
</template>

<style scoped>
.slider{
  width: 100%;
  height: 30rem;
  background: url(~/assets/photos/image1.jpg);
  background-position: cover;
  background-size: cover;
  
  margin-top:160px;
   position: relative;
  
 
}

.post1{
  margin-top: 2rem;
  padding-left: 8rem;
 
}
.home{
  overflow: hidden;
  background: rgb(219, 219, 219);
  padding-bottom: 2rem;

}
</style>