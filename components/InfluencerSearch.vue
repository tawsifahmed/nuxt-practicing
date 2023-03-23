<template>
  <div>
    <div class="col-lg-3 col-md-3 col-sm-12">
      <div class="searchbar-container">
        <div class="searchbar">
          <input
            type="text"
            id="searchInput"
            placeholder="Search Influencer's"
          />
          <div id="submitsearch"></div>
        </div>
        <div class="filter">
          <h1 class="filter-heading mb-2">Filter</h1>
          <div class="dropdown">
            <button
              class="btn btn dropdown-toggle"
              type="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              Select Category
            </button>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="#"></a></li>
              <li><a class="dropdown-item" href="#"></a></li>
              <li><a class="dropdown-item" href="#"></a></li>
            </ul>
          </div>
          <h1 class="filter-platform">Platform</h1>
          <div class="form-check">
            <input
              class="form-check-input"
              type="checkbox"
              value=""
              id="flexCheckChecked"
              checked=""
            />
            <label class="form-check-label pl-16 pt-1" for="flexCheckChecked">
              Facebook
            </label>
          </div>
          <div class="form-check">
            <input
              class="form-check-input"
              type="checkbox"
              value=""
              id="flexCheckDefault"
            />
            <label class="form-check-label pl-16 pt-1" for="flexCheckDefault">
              Youtube
            </label>
          </div>
          <div class="form-check">
            <input
              class="form-check-input"
              type="checkbox"
              value=""
              id="flexCheckDefault"
            />
            <label class="form-check-label pl-16 pt-1" for="flexCheckDefault">
              Instagram
            </label>
          </div>
          <div class="form-check">
            <input
              class="form-check-input"
              type="checkbox"
              value=""
              id="flexCheckDefault"
            />
            <label class="form-check-label pl-16 pt-1" for="flexCheckDefault">
              Tiktok
            </label>
          </div>
        </div>
        <span class="filter-hr"></span>
      </div>
      <div class="buttons pl-3">
        <h1 class="buttons-subscribe">Subscribe Range</h1>
        <button type="button" class="btn btn-active">
          <span class="btn-active-txt">0-50k</span>
        </button>
        <button type="button" class="btn btn">
          <span class="btn-txt">51k-100k</span>
        </button>
        <button type="button" class="btn btn">
          <span class="btn-txt">101k-500K</span>
        </button>
        <button type="button" class="btn btn">
          <span class="btn-txt">500k-1M</span>
        </button>
        <button type="button" class="btn btn">
          <span class="btn-txt">1.1M-10M</span>
        </button>
        <button type="button" class="btn btn">
          <span class="btn-txt">10M+</span>
        </button>
      </div>
      <div class="pb-1 pl-3">
        <input type="range" class="form-range" id="customRange1" />
        <div class="range-label">
          <p class="range-label-left">1k</p>
          <p class="range-label-right">10M+</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "InfluencerSearch",
};
</script>

<style>
.searchbar-container {
  padding: 10px;
}
.col-md-3 {
  height: 100%;
  background: #f6f6f6;
  border-radius: 16px;
}
.filter-heading {
  width: 44px;
  font-family: "Montserrat";
  font-weight: 700;
  font-size: 16px;
  line-height: 14px;
  color: #4a5654;
  margin-top: 32px;
}
.filter-platform {
  font-family: "Montserrat";
  font-size: 16px;
  line-height: 14px;
  color: #7b8d9e;
  margin-top: 24px;
  text-align: left;
  margin-bottom: 27px;
}
.filter .dropdown {
  background: #ffffff;
  border: 0.5px solid #c1c5d6;
  border-radius: 5px;
}
.filter .dropdown-toggle {
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 32px;
  display: flex;
  align-items: center;
  color: #7b8d9e;
  padding: 12px 111px 12px 20px;
}
.filter .btn.show {
  border: none;
  width: 100%;
  border-radius: 5px;
}
.filter-hr {
  color: 0.5px solid #c1c5d6;
  margin-bottom: 24px !important;
}
.heading-desc-sec {
  text-align: center;
}
input:focus {
  outline-offset: -2px;
}
.form-check-input:checked {
  background-color: #0bf7c7;
  border-color: #0bf7c7;
}
#submitsearch {
  border: 1px solid rgb(138, 134, 134);
  margin-left: -82px;
  padding: 5px;
  border-radius: 5px;
  cursor: pointer;
  padding-left: 10px;
  padding-right: 8px;
  padding-top: 4px;
  display: none;
  box-shadow: 0 0 1px black;
  margin-right: 110px;
}
#searchInput {
  font-size: 16px;
  background-color: white;
  background-image: url("https://cdn2.iconfinder.com/data/icons/ios-7-icons/50/search-24.png");
  background-position: 10px 17px;
  background-repeat: no-repeat;
  padding: 8px 20px 8px 40px;
  transition: width 0.8s ease-in-out;
  outline: none;
  opacity: 0.9;
  height: 56px;
  border: 0.5px solid #c1c5d6;
  border-radius: 5px;
  margin-top: 26px;
  width: 100%;
}
.buttons {
  text-align: left;
}
.buttons-subscribe {
  font-family: "Montserrat";
  font-size: 16px;
  line-height: 14px;
  color: #7b8d9e;
  margin-bottom: 24px;
}
.buttons .btn-active {
  padding: 10px;
  background: #00c79e;
  border: 0.5px solid #c5ede4;
  border-radius: 4px;
}
.buttons .btn-active-txt {
  font-family: "Montserrat";
  line-height: 14px;
  color: #ffffff;
  padding: 10px;
}
.buttons .btn {
  padding: 10px;
  border: 0.5px solid #c1c5d6;
  border-radius: 4px;
  margin-bottom: 16px;
  margin-right: 16px;
}
.buttons .btn-txt {
  font-family: "Montserrat";
  line-height: 14px;
  color: #7b8d9e;
}
.range-label {
  display: flex;
  margin-bottom: 30px;
  gap: 160px;
  margin-top: 8px;
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 14px;
  color: #7b8d9e;
}
.range-label-left,
.range-label-right {
  width: 50%;
}
.range-label-left {
  float: left;
}
label {
  position: absolute;
  display: inline-block;
  left: 154px;
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 14px;
  color: #7b8d9e;
}
</style>