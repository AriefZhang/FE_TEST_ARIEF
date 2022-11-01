<template>
  <div class="page_two_wrapper h-100 overflow-hidden">
    <img
      class="page_two_background position-absolute w-100"
      src="@/assets/ASSET_PNG/BG_Page_2.jpg"
      alt=""
      ref="bgImg"
    />
    <img
      class="page_two_trinket_bot-left position-absolute"
      src="@/assets/ASSET_PNG/Flower_2.png"
      alt=""
    />
    <div class="text-center m-auto w-75">
      <h1 class="page_two_title page_two_color_beige">Assalamualaikum Wr. Wb.</h1>
      <p class="m-0 mt-2">Tanpa mengurangi rasa hormat, Kami mengundang Bapak/Ibu/Saudara/i pada acara pernikahan kami:</p>
      <h1 class="page_two_name m-0 mt-4">Mustika</h1>
      <p class="m-0">Putri dari Bpk Winarno & Ibu Julaikah</p>
      <h1 class="page_two_name m-2">&</h1>
      <h1 class="page_two_name m-0">Wira</h1>
      <p class="m-0">Putri dari Bpk Winarno & Ibu Julaikah</p>
      <h1 class="page_two_title page_two_color_beige m-0 mt-3">QS. Ar-Rum Ayat 21</h1>
      <p class="m-0 page_two_ayat mt-1">Dan diantara tanda-tanda (kebesaran)-Nya ialah Dia menciptakan pasangan-pasangan untukmu dari jenismu sendiri, agar kamu cenderung dan merasa tenteram kepadanya, dan Dia menjadikan di antaramu rasa kasih dan sayang. Sungguh, pada yang demikian itu benar-benar terdapat tanda-tanda (kebesaran Allah) bagi kaum yang berpikir.</p>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>
.page_two_wrapper {
  padding-bottom: 38%;
  color: rgba(97, 118, 75, 1);
  font-family: 'Times New Roman', Times, serif;
}

.page_two_background {
  left: 0;
  top: 0;
}

.page_two_trinket_bot-left {
  width: 115%;
  left: -10%;
  bottom: -20%;
}

.page_two_title {
  font-style: italic;
  font-weight: 700;
  font-size: 24px;
  margin-top: 50%;
  margin-bottom: 0
}

.page_two_name {
  font-weight: 500;
  font-size: 68px;
  line-height: 68px;
}

.page_two_pic_profile_outer_wrapper {
  width: 49.75%;
  margin-top: 33.5%;
  top: 0;
  left: 25%;
  border-radius: calc(100vw * 0.5);
  border: 2px solid rgba(97, 118, 75, 0.5);
  background-color: transparent;
}

.page_two_pic_profile_inner_wrapper {
  border-radius: calc(100vw * 0.5);
  border: 5px solid transparent;
}

.page_two_ayat {
  font-size: 12px;
}

.page_two_color_beige {
  color: rgb(170, 139, 86);
}
</style>