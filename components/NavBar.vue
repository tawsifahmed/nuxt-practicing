<template>
  <nav class="navbar">
    <div class="nav-f">
      <img src="../assets/images/marvel-logo.svg" height="" alt="" />
    </div>
    <ul class="nav-m flex">
      <li>
        <a class="text-black font-light hover:font-bold" href="">Home</a>
      </li>
      <li>
        <a class="text-black font-light hover:font-bold" href="">Brands</a>
      </li>
      <li>
        <a class="text-black font-light hover:font-bold" href="">Influencer</a>
      </li>
      <li>
        <a class="text-black font-light hover:font-bold" href="">Service</a>
      </li>
      <li>
        <a class="text-black font-light hover:font-bold" href="">News Feed</a>
      </li>
      <li class="search-logo">
        <img src="../assets/images/searchbar-logo.svg" alt="" />
      </li>
    </ul>
    <div class="nav-l">
      <a class="text-white" href="">Sign In</a>
    </div>
  </nav>
</template>

<script>
export default {
  name: "NavBar",
};
</script>


<style>
.navbar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding-top: 10px;
  margin: 0 auto;
  width: 80%;
  top: 0;
}
.navf {
  filter: brightness(12);
}

.nav-m li {
  display: inline;
  padding-right: 50px;
}

.nav-m a {
  text-decoration: none;
}

.nav-l {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
  padding-right: 20px;
}
.nav-l a {
  text-decoration: none;
  border: 1px solid rgba(0, 199, 158, 1);
  background-color: rgba(0, 199, 158, 1);
  margin-left: 60px;
  padding: 8px 15px 8px 15px;
  border-radius: 5px;
}
.nav-l a:hover {
  transition: 2s;
  background-color: rgb(21, 179, 148);
  color: white;
}

.search-logo {
  cursor: pointer;
}
</style>