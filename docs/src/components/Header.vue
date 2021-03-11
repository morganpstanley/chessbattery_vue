<template>
  <div id="header">
    <div id="logo">
      <img src='../assets/lightning.svg' id="logo-image" alt="lighting-bolt" />
        <span id="chess">CHESS</span>
        <span id="battery">BATTERY</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style scoped>
#header {
  position: absolute;
  top: 0px;
  left: 0px;
  width: 100vw;
  height: 4rem;
  background-color: seagreen;
  display: flex;
  align-items: center;
  justify-content: center;
}

#logo-image {
  filter: drop-shadow(1px 1px 3px yellow);
  width: 1rem;
}

#logo{
  font-size: 1.4rem;
  color: seashell;
}

#logo-area {
  margin: 10px;;
}

span#battery {
  font-weight: 700;
}
</style>
