<template>
  <div class="card">
    <div class="event-image">
      <h4>splash event</h4>
    </div>

    <div class="description">
      <p>
        <span class="desc"
          >Lorem Ipsum is simply dummy text of the printing and typesetting
          industry.</span
        >
      </p>
    </div>

    <div class="details">
      <p>date</p>
      <p>location</p>
    </div>
    <div class="btn">
      <button>More details</button>
    </div>
  </div>
</template>


<style scoped>

.desc{
    display: block;
    font-size: 14px;
    font-family: 'Montserrat', sans-serif;
    font-weight: normal;
    color: #666666;
}

.description{
    width: 80%;
    height: fit-content;
    padding-left: 20px;
}
.card{
    width: 18rem;
    height: 28rem;
    border-radius: 1rem;
    position: relative;
    border-radius: 1rem;
    background: white;
     font-family: 'Oswald', sans-serif;
}

p{
    font-size: 14px;
    font-weight: normal;
    margin-top: 1rem;
    
}

.event-image{
    width: 100%;
    height: 14rem;
    background: url(~/assets/photos/image2.jpg);
    background-size: cover;
    background-position: center;
    border-top-right-radius: 1rem;
    border-top-left-radius: 1rem;
}
.btn{
    text-align: center;
    position: relative;
    margin-top: 2rem;
}

h4{
    position: absolute;
    margin-left: 20px;
    margin-top: 10rem;
    color: white;
    font-size: 24px;
    font-weight: bold;
}

.details{
    padding-left: 20px;
     width: 80%;
    height: fit-content;
}
button{
    padding: 0.5rem 4rem;
    border-radius: 0.3rem;
    border: none;
    background:#2680EB;
    color: white;
     font-family: 'Oswald', sans-serif;
     position: relative;
}
</style>