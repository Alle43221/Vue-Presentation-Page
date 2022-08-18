<template>
  <div class="projects">
  <div class="obj">
    <h2>JoyXChange App by Team Swoosh - Technovation Girls 2022</h2>
    <div class="info">
      <img src="@/assets/4.png" alt="JoyXChange app preview">
      <div class="links">
        <h3>🎉Romanian semifinalist project</h3>
        <h3>All about our app here:</h3>
        <p><a href="https://www.technovation.org/blogs/2022-semifinalist-teams/" target="_blank" rel="noopener">
        Technovation's article about all the semifinalists</a></p>
        <p><a href="https://adfaber.org/o-echipa-de-eleve-din-romania-a-impresionat-o-lume-intreaga-sunt-castigatoare-in-competitia-de-programare-si-antreprenoriat-technovation-girls/" target="_blank" rel="noopener">AdFaber's article about Romanian semifinalists</a></p>
        <p><a href="https://youtu.be/owNmk7XrEvw" target="_blank" rel="noopener">Demo video on Youtube</a></p>
        <p><a href="https://www.youtube.com/watch?v=HnqALTBwO74&ab_channel=JoyXchange" target="_blank" rel="noopener">Pitch video on Youtube</a></p>
        <p><a href="https://www.instagram.com/joyxchange.2022/?igshid=YmMyMTA2M2Y%3D" target="_blank" rel="noopener">Instagram account for our project</a></p>
      </div>
    </div>
    </div>
    <div class="obj">
    <h2>Romanian Informatics Olympiad 2022</h2>
    <div class="info">
        <img src="@/assets/logo.png" alt="SEPI logo">
      <div class="links">
        <p><a href="https://sepi.ro/" target="_blank" rel="noopener">Official competition website</a></p>
        <h3>Results:</h3>
        <p><a href="https://drive.google.com/file/d/1cYmjg__q_LEUfTEO6gVEkwIKL9aD3LR1/view" target="_blank" rel="noopener">
        National Participation</a></p>
        <p><a href="https://drive.google.com/drive/folders/1nk26suZJX335Ca-fPJgC31LePxjn0Fu5" target="_blank" rel="noopener">
        🥈2nd Regional Place</a></p>
      </div>
    </div>
  </div>
   <div class="obj">
    <h2>Hygea+ App by Team HygeniusCoders - Technovation Girls 2021</h2>
    <div class="info">
      <img src="@/assets/Screenshot 2022-08-15 120809.png" alt="Hygea+ app preview">
      <div class="links">
        <h3>All about our app here:</h3>
        <p><a href="https://hygeaplus.wixsite.com/hygeaplus/home" target="_blank" rel="noopener">App's dedicated website</a></p>
        <p><a href="https://www.youtube.com/watch?v=MSFm0twIKp4&ab_channel=HygeniusCoders" target="_blank" rel="noopener">Demo video on Youtube</a></p>
        <p><a href="https://www.instagram.com/hygea.plus/" target="_blank" rel="noopener">Instagram account for our project</a></p>
      </div>
    </div>
  </div>
  <div class="obj">
    <h2>Romanian Informatics Olympiad 2021</h2>
    <div class="info">
        <img src="@/assets/download.png" alt="OSEPI logo">
      <div class="links">
        <p><a href="https://srsi.ro/osepi" target="_blank" rel="noopener">Official competition website</a></p>
        <h3>Results:</h3>
        <p><a href="https://srsi.ro/static/awards/oji/SM.pdf" target="_blank" rel="noopener">
        🥈2nd Regional Place</a></p>
      </div>
    </div>
  </div>
  <div class="obj">
    <h2>"Le pied a coulisse et le micromètre"
      - CFA Prix Romania 2021</h2>
    <div class="info">
      <img src="@/assets/Screenshot 2022-08-15 145652.png" alt="Project photo">
      <div class="links">
        <h3>Team: Les petites artisans</h3>
         <p><a href="http://www.premiilecfa.ro/" target="_blank" rel="noopener">Official competition website</a></p>
          <p><a href="https://www.facebook.com/premiilecfa" target="_blank" rel="noopener">Official competition Facebook profile</a></p>
          <p><a href="https://www.facebook.com/premiilecfa/photos/pcb.2825654851021432/2825684767685107" target="_blank" rel="noopener">Results</a></p>
      </div>
    </div>
  </div>
  <div class="obj">
    <h2>"La maison de l'avenir"
      - CFA Prix Romania 2020</h2>
    <div class="info">
      <img src="@/assets/Screenshot 2022-08-15 150328.png" alt="Project photo">
      <div class="links">
        <h3>Team: Les petites architectes</h3>
         <p><a href="http://www.premiilecfa.ro/" target="_blank" rel="noopener">Official competition website</a></p>
          <p><a href="https://www.facebook.com/premiilecfa" target="_blank" rel="noopener">Official competition Facebook profile</a></p>
          <p><a href="https://www.facebook.com/premiilecfa/photos/ms.c.eJxFzMkNwDAMA8GOAh2kjv4bC2I78newpNEynQAUkdKPHYgNOWCJEgF~_oOzCB3QVzgFKqXtc6G8SPR9hq2Bd2IW~_NYYe1Q~-~-.bps.a.2527735414146712/2527735444146709" target="_blank" rel="noopener">Results</a></p>
      </div>
    </div>
  </div>
  </div>
</template>

<style scoped>
.projects h2{
  margin:20px 20px 0 20px;
  text-decoration:underline;
}
.info{
  display:flex;
  flex-direction: row;
   align-items: center;
}
.info img{
  width:55vh;
  margin:20px;
  border-radius: 5px;
}
.links{
  margin: 20px;
}
.links a{
  text-decoration: none;
  color:#264653;
}
.links a:hover{
  text-decoration: underline;
  color:#E9EBED;
}
.obj{
  margin: 20px;
  border-radius: 0.6vh;
  background: liniar-gradient(#E9EBED, #D3D6DA);
  text-align: justify;
  width:100%;
  border: 3px solid #E9EBED;
}
.projects{
  display: flex;
  flex-direction: column;
  justify-content: center;
  width: 95%;
}
</style>
