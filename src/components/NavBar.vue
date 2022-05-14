<script></script>

<template>
    <nav class="ContainerNavigation">
        <div class="ContainerLogo">
            <span class="Logo">Axojonautas</span>
        </div>
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
                <a class="link" href="#">Donaciones</a>
            </li>
        </ul>
    </nav>
</template>

<style>
.ContainerNavigation {
  position: relative;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 20px;
  color: black;
  text-transform: uppercase;
  overflow: hidden;
}
.ContainerLogo {
    display: flex;
}
.Logo {
      padding-left: 4px;
    }

.navigation {
    display: flex;
    list-style-type: none;
}

    li {
      opacity: 1;
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
        color: black;

        &:hover {
          color: #ea4f4c;
        }
      }
</style>