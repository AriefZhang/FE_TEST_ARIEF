<template>
  <div class="page_one_wrapper h-100 overflow-hidden">
    <img
      class="page_one_background position-absolute w-100"
      src="@/assets/ASSET_PNG/BG_Page_1.jpg"
      alt=""
      ref="bgImg"
    />
    <img
      class="page_one_trinket_top_right position-absolute"
      src="@/assets/ASSET_PNG/Flower_4.png"
      alt=""
    />
    <img
      class="page_one_trinket_mid_right position-absolute"
      src="@/assets/ASSET_PNG/Leaf_1.png"
      alt=""
    />
    <img
      class="page_one_trinket_mid_left position-absolute"
      src="@/assets/ASSET_PNG/Leaf_2.png"
      alt=""
    />
    <img
      class="page_one_trinket_bot-right position-absolute"
      src="@/assets/ASSET_PNG/Flower_4.png"
      alt=""
    />
    <h1 class="page_one_title text-center">The Wedding of</h1>
    <div class="page_one_pic_profile_outer_wrapper position-absolute overflow-hidden">
      <div class="page_one_pic_profile_inner_wrapper overflow-hidden">
        <img
        class="page_one_pic_profile"
        src="@/assets/ASSET_PNG/Photo_Profil.png"
        alt=""
        />
      </div>
    </div>
    <h1 class="page_one_groom_and_bride text-center">Mustika & Wira</h1>
    <div class="d-flex flex-column align-items-center mt-5">
      <div class="page_one_date_wrapper d-flex flex-row align-items-center justify-content-around w-50">
        <div>25</div>
        <div class="page_one_date_divider">05</div>
        <div class="page_one_date_divider">2022</div>
      </div>
      <p class="mt-2">di mohon kehadirannya</p>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>
.page_one_wrapper {
  padding-bottom: 10%;
  color: rgba(97, 118, 75, 1);
  font-family: 'Times New Roman', Times, serif;
}

.page_one_background {
  left: 0;
  top: 0;
}

.page_one_trinket_top_right {
  transform: rotate(5deg);
  width: 60%;
  right: -25%;
  top: -10%;
}

.page_one_trinket_mid_right {
  right: 10%;
  bottom: 34%;
  width: 13%;
}

.page_one_trinket_mid_left {
  left: 10%;
  top: 50%;
  width: 13%;
}

.page_one_trinket_bot-right {
  transform: rotate(-20deg);
  width: 60%;
  right: -35%;
  bottom: -5%;
}

.page_one_title {
  font-weight: 700;
  font-size: 38px;
  margin-top: 18%;
  margin-bottom: 0
}

.page_one_pic_profile_outer_wrapper {
  width: 49.75%;
  margin-top: 33.5%;
  top: 0;
  left: 25%;
  border-radius: calc(100vw * 0.5);
  border: 2px solid rgba(97, 118, 75, 0.5);
  background-color: transparent;
}

.page_one_pic_profile_inner_wrapper {
  border-radius: calc(100vw * 0.5);
  border: 5px solid transparent;
}

.page_one_pic_profile {
  width: 115.75%;
}

.page_one_groom_and_bride {
  font-weight: 400;
  font-size: 72px;
  line-height: 78px;
  color: rgba(97, 118, 75, 1);
  margin-top: 100%;
  margin-inline: auto;
  width: 55%;
  margin-bottom: 0;
}

.page_one_date_wrapper {
  font-size: 36px;
  line-height: 38px;
  padding: 5px 15px;
  border: 3px solid rgb(249, 183, 84)
}

.page_one_date_wrapper > div {
  font-weight: 500;
  padding-inline: 10px;
}

.page_one_date_divider {
  border-left: 3px solid rgba(97, 118, 75, 1);
}
</style>