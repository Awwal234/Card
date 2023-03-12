<script lang="ts">
import { defineComponent } from 'vue'
export default defineComponent({
  data() {
    return {
      qr_title: 'Improve your front-end skills by building projects',
      qr_sub: 'Scan the QR code to visit Frontend Mentor and take your coding skills to the next level'
    }
  }
})
</script>

<template>
  <main class="py-[100px]">
    <div class="w-[90%] rounded-xl md:w-[300px] mx-auto p-[16px] bg-[#fff]">
      <img src="/qrcode.png" class="rounded-xl" alt="" />
      <div class="mt-[20px] space-y-[20px]">
        <div class="mx-auto font-[700] font-[Outfit] text-[25px] md:text-[23px] title text-center">
          {{ qr_title }}
        </div>
        <div
          class="mx-auto w-[85%] font-[400] font-[Outfit] text-[17px] md:w-[95%] pb-[30px] md:text-[18px] sub text-center">
          {{ qr_sub }}
        </div>
      </div>
    </div>
  </main>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap');

.title {
  color: hsl(218, 44%, 22%);
}

.sub {
  color: hsl(212, 45%, 89%);
}
</style>
