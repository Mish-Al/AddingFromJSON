<template>
  <div id="products">
  
  </div>
</template>
<script>

  async function getChips(){
    const chips = await fetch('https://mish-al.github.io/jsonServer/file.json')
    const jsonChips = await chips.json()
    console.log(jsonChips);
    let fetchedData = jsonChips.chips

    const display = document.querySelector('#products')

    fetchedData.forEach(chips =>{
      display.innerHTML += `
      <div class="card">
          <img src="" style="width: 18rem" alt="">
          <div class="card-body">
            <h3 class="card-title">${chips.name}</h3>
            <p class="card-text">${chips.manufacturer}</p>
          </div>
        </div>
    `
  })
 }
 getChips()
 </script>
 <style>
    #products {
      height: 100vh;
    }
</style>