<template>
  <nav
    class="flex justify-between container mx-auto xl:px-40 md:px-20 px-10 py-10"
  >
    <div></div>
    <h1>
      <img src="../public/logo.svg" alt="logo" />
    </h1>
    <div class="md:flex hidden gap-5 font-medium text-sm">
      <button
        class="border active:scale-105 rounded-md h-9 w-28 border-[#1A6DFF] text-[#1A6DFF] hover:bg-[#1A6DFF] hover:text-white"
      >
        로그인
      </button>
      <button
        class="border active:scale-105 rounded-md h-9 w-28 border-[#1A6DFF] bg-[#1A6DFF] text-white hover:bg-white hover:text-[#1A6DFF]"
      >
        회원가입
      </button>
    </div>
    <div class="md:hidden font-medium text-xs my-auto">
      <button
        class="border active:scale-105 rounded-md h-5 w-14 border-[#1A6DFF] text-[#1A6DFF] hover:bg-[#1A6DFF] hover:text-white"
      >
        다운로드
      </button>
    </div>
  </nav>
</template>

<script setup></script>

<style lang="scss" scoped></style>
