<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/pp.png" style="height: 50vh">
    <div class="hello">
    <h1>BOOOOO!</h1>
    <h2>
      Hi there! Here's some basic info about me:
    </h2>
    <ul>
      <li style="margin:10px 0">First Name: Alexandra-Ioana</li>
      <li style="margin:10px 0">Last Name: Moroz</li>
      <li style="margin:10px 0">Age: 17</li>
      <li style="margin:10px 0">Education:
        <ul>
        <li><a href="https://www.eminescusm.ro/">Mihai Eminescu National College</a></li>
        <li><a href="https://balcescupetofi.ro/ro/">Balcescu-Petofi Elementary School</a></li>
        </ul>
      </li>
      <li style="margin:10px 0">Foreign Languages Level:
        <ul>
        <li>English Cambridge Exam C1A</li>
        <li>Das Deutsche Sprachdiplom der Kultusministerkonferenz B1</li>
        </ul>
      </li>
    </ul>
    <hr style="border-top: solid 3px #264653; border-bottom: none;">
    <br>
      <button><a href="/about">Programming and Design</a></button>
  </div>
    <HelloWorld/>
  </div>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
button{
  background: #264653;
  border-radius: 5px;
  border: solid 3px #D3D6DA;
  height: 7.5vh;
}

button a{
  color:#D3D6DA;
  font-size: 1.5em;
}

button a:hover{
  color:#E9EBED;
  text-decoration: none;
}

h3 {
  margin: 40px 0 0;
}

.hello{
  max-width: 70vh;
  margin: 20px 0;
}

a{
  color:#264653;
  text-decoration: none;
}

.home{
  width: 100%;
  display:flex;
  flex-direction: row;
  font-weight: bold;
  justify-content: space-around;
  align-items: center;
}

img{
  margin:20px;
}

a:hover{
  color:#D3D6DA;
  text-decoration: underline;
}

a.router-link-exact-active {
  color: #D3D6DA;
}

ul{
text-align: left;
}
</style>
