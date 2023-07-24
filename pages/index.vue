<template> 
  <div class="container mx-auto"> 
    <div class="grid grid-cols-4 gap-x-6"> 
      <div> 
        <InfluencerSearch /> 
      </div> 
      <div class="col-span-3 bg-slate-50 rounded-lg"> 
        <div class="grid grid-cols-3 p-4 gap-x-4"> 
          <InfluencerList /> 
          <InfluencerList /> 
          <InfluencerList /> 
          <InfluencerList /> 
        </div> 
      </div> 
    </div> 
  </div> 
</template> 
 
<script> 
import Header from "@/components/Header"; 
import influencerSearch from "@/components/influencerSearch"; 
import InfluencerList from "@/components/InfluencerList"; 
export default { 
  name: "IndexPage", 
  components: { 
    Header, 
    influencerSearch, 
    InfluencerList, 
  }, 
}; 
</script> 
 
<style> 
.card { 
  width: 180px; 
  border-radius: 10px; 
} 
.card-img-top-ellipse { 
  margin-top: -60px; 
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