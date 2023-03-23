<template>
  <div>
    <!---------- navbar ------------------>
    <div class="container mx-auto">
      <header class="header text-black">
        <NavBar />

        <InfluencerBanner class="mb-20" />
      </header>
    </div>
  </div>
</template>

<script>
import NavBar from "@/components/NavBar";
import InfluencerBanner from "@/components/InfluencerBanner";
export default {
  name: "Header",
  components: {
    NavBar,
    InfluencerBanner,
  },
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