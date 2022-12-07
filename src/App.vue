<template>
  <div id="app">
    
    <router-view/>
  </div>
</template>

<style>

@import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,500;1,300;1,400;1,500&display=swap');

@import url('https://fonts.googleapis.com/css2?family=Dancing+Script&family=Open+Sans:ital,wght@0,300;0,400;0,500;1,300;1,400;1,500&display=swap');

@import url('https://fonts.googleapis.com/css2?family=Cinzel&family=Dancing+Script&family=Open+Sans:ital,wght@0,300;0,400;0,500;1,300;1,400;1,500&display=swap');
:root{
  --themeColor:rgb(195, 144, 57);
}

h1,h2,h3,h4,h5{
  font-family: cinzel;
  
}
p{
  font-family: itali;
  font-size: 18px;
}
.title {
  color: white;
  background: var(--themeColor);
  height: 85px;
  text-align: center;
  display: flex;
  justify-content: center;
  padding-top: 16px;
}



</style>
