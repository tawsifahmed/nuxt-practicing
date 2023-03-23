<template>
  <div class="card">
    <img
      style="border-top-left-radius: 10px; border-top-right-radius: 10px"
      src="../assets/images/Subtract.png"
      class=""
      alt="..."
    />
    <div class="card-body">
      <img
        style="width: 98px"
        src="../assets/images/Ellipse.1.svg"
        class="card-img-top-ellipse"
      />
      <h5 class="card-title text-center">Nadir on the go</h5>
      <p class="card-subtitle text-center">Nadir Nibras</p>
      <p class="card-text text-center">Travel Filmmaker</p>
      <span class="card-hr"><hr /></span>
      <div class="social-link pl-14 pb-4">
        <div class="fb">
          <p class="like-follower">157K likes</p>
          <p class="like-follower">628K followers</p>
        </div>
        <div class="insta">
          <p class="like-follower">166K</p>
          <p class="like-follower">followers</p>
        </div>
        <div class="yt">
          <p class="like-follower">784K</p>
          <p class="like-follower">subscribers</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "InfluencerList",
};
</script>


<style>
.card {
  width: 180px;
  border-radius: 10px;
}
.card-img-top-ellipse {
  margin-top: -56px;
  margin-left: 132px;
}
.card-title {
  margin-top: 10px;
  font-family: "Montserrat";
  font-weight: 700;
  font-size: 19px;
  line-height: 28px;
  text-transform: capitalize;
  margin-bottom: 10px;
}
.card-subtitle {
  font-family: "Abril Fatface";
  font-size: 24px;
  line-height: 24px;
  color: #00c79e;
  margin-bottom: 3px;
}
.card-text {
  font-family: "Montserrat";
  font-size: 14px;
  line-height: 24px;
  color: #7b8d9e;
  margin-bottom: 15px;
}
.card-hr {
  background: #c1c5d6;
  width: 100px;
}
.social-link {
  display: flex;
  margin-top: 24px;
}
.social-link-logo,
.social-link-links {
  width: 50%;
}
.social-link-links {
  display: flex;
}
.fb,
.insta,
.yt {
  width: 33.33%;
}
.footer-links {
  display: flex;
  flex-direction: row;
}
.border-bottom {
  border-bottom: none !important;
}

/* ss */
.card {
  width: auto !important;
  margin-bottom: 28px;
}
.card-body {
  background: #f6f6f6;
  border-radius: 16px;
}

.form-range {
  background: #c1c5d6;
  border-radius: 8px;
}

.like-follower {
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 500;
  font-size: 11px;
  line-height: 14px;
  color: #7b8d9e;
  margin-bottom: 5px;
}
</style>