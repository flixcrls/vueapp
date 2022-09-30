<template>
  <nav>
    <a href="/" class="logo">
      Logo
    </a>
    <ul class="menu">
      <li class="active"><a href="#main">Home</a></li>
      <li><a href="#discover">Discover</a></li>
      <li><a href="#register">Register</a></li>
      <li><a href="#">🔍</a></li>
    </ul>
  </nav>
  <div class="main">
    <p class="main-text"><strong>Booked Tool</strong> enable you to<br>create interactive advertisement</p>
    <button class="main-btn">What is it?</button>
  </div>
  <div class="login">
    <p class="login-text">please login to start using<br><strong>Booked Tools</strong></p>
    <input type="text" placeholder="Email">
    <input type="text" placeholder="Password">
    <button class="login-btn">Login</button>
  </div>
  <h1 class="dis-text"><strong>DISCOVER</strong> <br> BOOKED TOOL</h1>
  <div class="discover">
    <ul class="dis-ul">
      <li><a href="">Discover A</a></li>
      <li><a href="">Discover B</a></li>
      <li><a href="">Discover C</a></li>
      <li><a href="">Discover D</a></li>
    </ul>
  </div>
  <p class="dis-lor">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Possimus optio error dicta magni, totam
    odio, autem
    aliquid quam similique quia eveniet iste aperiam qui eum? Voluptate iste doloribus deserunt nemo ipsum
    necessitatibus inventore vel sapiente incidunt assumenda dolorum ex natus dolorem, laboriosam ad commodi facere
    molestias? Facilis fugiat rem eos error itaque maxime quia quidem! Omnis, delectus ducimus nulla dolore dignissimos
    consectetur necessitatibus fugiat earum impedit voluptatem velit dolores veritatis ea repellendus asperiores
    repudiandae saepe? Totam neque inventore est aliquid.</p>
  <div class="git">
    <h1 class="git-text">Get in touch</h1>
    <p class="git-text">want to get in touch? we love to hear from you. Here's how you can reach us...</p>
    <input class="git-inp" type="text" placeholder="🔍 search...">
  </div>
</template>

<script>

export default {
  name: 'App',

}
</script>

<style lang="scss">
body {
  margin: 0px;
  padding: 0px;
  background-color: white;
}

ul {
  list-style: none;
}

a {
  text-decoration: none;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  box-sizing: border-box;
  background-color: white;
}

.menu {
  display: flex;

  li a {
    padding: 15px;
    color: black;
    font-size: 20px;
    align-items: center;

    &:hover {
      background-color: rgb(225, 225, 225);
      border-radius: 50%;
      transition: all ease 0.4s;
    }
  }
}

.main {
  padding: 100px;
}

.main-text {
  font-size: 25px;
}

.main-btn {
  border: none;
  padding: 10px;
  background-color: rgb(145, 197, 239);
  font-size: 20px;
  border-radius: 5px;
}

.login {
  padding: 25px;
  background-color: rgb(225, 225, 225);
  display: flex;
  justify-content: space-evenly;
  align-items: center;
}

input {
  padding: 10px;
}

.login-btn {
  border: none;
  padding: 10px;
  background-color: rgb(145, 197, 239);
  font-size: 15px;
  border-radius: 5px;
}

.login-text {
  font-size: 17px;
}

.dis-text {
  text-align: center;
}

.discover {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  box-sizing: border-box;
  background-color: white;
}

.dis-lor {
  text-align: center;
}

.dis-ul {
  display: flex;

  li a {
    padding: 35px;
    color: black;
    font-size: 20px;
    align-items: center;
  }
}

.git {
  padding: 50px;
  background-color: rgb(225, 225, 225);
}

.git-text {
  text-align: center;
}

.git-inp {
  width: 100%;
  align-items: center;
}
</style>
