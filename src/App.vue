<template>
  <div id="app">
    <div id="nav_bar">
      <div>
        <h2>Moroz Alexandra-Ioana (Alle43221)</h2>
      </div>
    <nav>
      <router-link to="/">Get to know me</router-link>
      <router-link to="/projects">Projects</router-link>
      <router-link to="/about">About</router-link>
    </nav>
    </div>
    <div id="content">
    <router-view/>
    </div>
    <div id="footer">

      <a href="https://github.com/Alle43221" target="_blank" rel="noopener">
        <img src="@/assets/10.png" alt="Github social link" style="width:5vh">
        </a>
      <a href="https://www.facebook.com/alexandra.moroz.7524" target="_blank" rel="noopener">
        <img src="@/assets/15-1.png" alt="Another social link" style="width:5vh">
      </a>
      <a href="https://www.instagram.com/alle43221/" target="_blank" rel="noopener">
        <img src="@/assets/12.png" alt="Instagram social link" style="width:5vh">
      </a>
      <a href="mailto:allmoroz14@gmail.com" target="_blank" rel="noopener">
        <img src="@/assets/email.png" alt="Email icon" style="width:5vh">
      </a>
      <a id="discord" target="_blank" rel="noopener">
        <img src="@/assets/13.png" alt="Discord icon" style="width:6vh; cursor: pointer;"
        v-on:click="copyURL('Alle43221#8359')"
        v-on:keyup="copyURL('Alle43221#8359')">
      </a>
       <a href="https://www.printables.com/social/254384-alle43221/about" target="_blank" rel="noopener">
        <img src="@/assets/prusa.png" alt="Prusa icon" style="width:6vh">
      </a>
    </div>
  </div>
</template>

<script lang="ts">

export default ({
  methods: {
    async copyURL(mytext:string) {
      try {
        await navigator.clipboard.writeText(mytext);
        alert('Discord ID copied to clipboard.');
      } catch ($e) {
        alert('Cannot copy Discord ID to clipboard.');
      }
    },
  },
});

</script>

<style>

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #264653;
}

h1, h2, h3{
  text-decoration: none;
}

nav {
  padding: 20px;
  display: flex;
  margin: 0;
  justify-content: space-between;
}

nav a {
  color: #264653;
  font-weight: bold;
  font-size:1.2rem;
  margin: 0 20px;
  text-decoration: none;
}

nav a:hover{
  color:#5D5D83;
}

nav a.router-link-exact-active {
  color: #5D5D83;
  text-decoration: underline;
}

#nav_bar{
  background: linear-gradient(#D3D6DA, #B7B7CC);
  border-radius: 0 0 10px 10px;
  margin:0;
  padding: 0;
  border-bottom:solid 4px  #264653;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  align-items: center;
  height: 8.7vh;
}

#footer{
  background:  linear-gradient(#B7B7CC,#D3D6DA);

  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  font-size: 0.8em;
  font-weight: bold;
  font-family: 'Trispace', sans-serif;

  position:relative;
  bottom:0;
  height: 11.5vh;
  width: 100%;
  padding: 1.5vh 0 1.5vh 0;
  border-top-left-radius: 10px;
  border-top-right-radius: 10px;
  border-top: solid 0.6vh #264653;
}

#footer a{
  color:#264653;
  margin:10px 20px;
  font-size: 1rem;
}

#footer a:hover{
  color:#5D5D83;
  filter: brightness(0) saturate(100%) invert(39%) sepia(9%) saturate(1484%) hue-rotate(201deg)
  brightness(90%) contrast(90%);
}

#content{
    min-height: 58.5vh;
    display: flex;
    align-items: center;
    margin: 8vh auto;
    background:linear-gradient(#B7B7CC,#A0A0BB);
    width: 130vh;
    justify-items: center;
    border-radius:10px;
    border:solid 0.6vh #264653;
}
</style>
