<script></script>

<template>
    <nav class="ContainerNavigation">
            <img src="../assets/Logos/MicrosoftTeams-image.png" alt="">
        <ul class="navigation">
            <li class="parent">
                <a class="link" href="#">MAPA</a>
            </li>
            <li class="parent">
                <a class="link" href="#">About Us</a>
            </li>
            <li class="parent">
                <a class="link" href="#">Firmas</a>
            </li>
            <li class="parent">
                <a class="Donaciones" href="#">Donaciones</a>
            </li>
        </ul>
    </nav>
</template>

<style scoped>
.ContainerNavigation {
  position: relative;
  display: flex;
  align-items: center;
  justify-content: space-around;
  padding: 20px;
  color: white;
  text-transform: uppercase;
  overflow: hidden;
}

nav img{
  height: 200px;
  width: auto;
  justify-self: start;
  margin-left: 20px;
}

.navigation {
    display: flex;
    list-style-type: none;
}

    li {
      list-style-type: none;
      color: black;
      text-decoration: none;
      transition: all 0.3s ease-in-out;
    }

    .parent {
      padding: 0 10px;
      cursor: pointer;
    }
      .link {
        position: relative;
        display: flex;
        align-items: center;
        text-decoration: none;
        transition: all 0.3s ease-in-out;
        color: white;
        padding-top: 10px;
      }
      .Donaciones{
        position: relative;
        display: flex;
        align-items: center;
        text-decoration: none;
        transition: all 0.3s ease-in-out;
        color: white;

        padding: 10px;
        background-color: rgb(210, 145, 33);
        border-radius: 10%;
      }
</style>