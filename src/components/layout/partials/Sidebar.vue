<template>
  <div
    class="w-full lg:w-1/5 bg-gray-800 p-4 scroll-smooth h-screen overflow-y-auto [&::-webkit-scrollbar]:w-1 [&::-webkit-scrollbar-track]:bg-gray-100 [&::-webkit-scrollbar-thumb]:bg-gray-300 dark:[&::-webkit-scrollbar-track]:bg-neutral-700 dark:[&::-webkit-scrollbar-thumb]:bg-neutral-500"
  >
    <div class="flex items-center mb-8">
      <img
        alt="Truyen.cc logo"
        class="mr-2"
        height="50"
        src="https://storage.googleapis.com/a1aa/image/F2kmRUCRSm5iaNDpbDkfuwGePBhHgm0jhtzJeQrPxjU.jpg"
        width="50"
      />
      <span class="text-2xl font-bold">TRUYEN.cc</span>
    </div>
    <div class="mb-8">
      <div class="bg-blue-500 p-4 rounded-lg mb-4">
        <div class="flex items-center">
          <i class="fas fa-bell text-2xl mr-2"></i>
          <div>
            <div class="text-sm">Cập nhật hôm nay</div>
            <div class="text-xl font-bold">50</div>
          </div>
        </div>
      </div>
      <div class="bg-blue-500 p-4 rounded-lg">
        <div class="flex items-center">
          <i class="fas fa-book text-2xl mr-2"></i>
          <div>
            <div class="text-sm">Tổng số lượng truyện</div>
            <div class="text-xl font-bold">22880</div>
          </div>
        </div>
      </div>
    </div>
    <nav>
      <ul>
        <li class="mb-1">
          <a
            class="flex items-center font-bold text-sm px-3 py-4 rounded-lg transition duration-300 ease-in-out bg-gray-700"
            href="#"
          >
            <i class="fas fa-home mr-2"></i>Trang Chủ
          </a>
        </li>
        <li class="mb-1">
          <a
            class="flex items-center font-bold text-sm px-3 py-4 rounded-lg transition duration-300 ease-in-out hover:bg-gray-700"
            href="#"
          >
            <i class="fas fa-book-open mr-2"></i>Truyện mới
          </a>
        </li>
        <li class="mb-1">
          <a
            class="flex items-center font-bold text-sm px-3 py-4 rounded-lg transition duration-300 ease-in-out hover:bg-gray-700"
            href="#"
          >
            <i class="fas fa-book-reader mr-2"></i>Đang phát hành
            <span
              class="ml-auto bg-blue-500 text-white rounded-full p-1 text-xs"
              >18930</span
            >
          </a>
        </li>
        <li class="mb-1">
          <a
            class="flex items-center font-bold text-sm px-3 py-4 rounded-lg transition duration-300 ease-in-out hover:bg-gray-700"
            href="#"
          >
            <i class="fas fa-check mr-2"></i>Hoàn thành
            <span
              class="ml-auto bg-blue-500 text-white rounded-full p-1 text-xs"
              >3533</span
            >
          </a>
        </li>
        <li class="mb-1">
          <a
            class="flex items-center font-bold text-sm px-3 py-4 rounded-lg transition duration-300 ease-in-out hover:bg-gray-700"
            href="#"
          >
            <i class="fas fa-clock mr-2"></i>Sắp ra mắt
            <span
              class="ml-auto bg-blue-500 text-white rounded-full p-1 text-xs"
              >417</span
            >
          </a>
        </li>
        <li class="mb-1">
          <a
            class="flex items-center font-bold text-sm px-3 py-4 rounded-lg transition duration-300 ease-in-out hover:bg-gray-700"
            href="#"
          >
            <i class="fas fa-users mr-2"></i>Subteam
            <span
              class="ml-auto bg-red-500 text-white rounded-full px-2 py-1 text-xs"
              >0</span
            >
          </a>
        </li>
        <li class="mb-1">
          <a
            class="flex items-center font-bold text-sm px-3 py-4 rounded-lg transition duration-300 ease-in-out hover:bg-gray-700"
            href="#"
          >
            <i class="fas fa-list mr-2"></i>Thể loại
          </a>
        </li>
        <li class="mb-1">
          <a
            class="flex items-center font-bold text-sm px-3 py-4 rounded-lg transition duration-300 ease-in-out hover:bg-gray-700"
            href="#"
          >
            <i class="fas fa-code mr-2"></i>API Document
          </a>
        </li>
      </ul>
    </nav>
  </div>
</template>

<script setup>
import { ref } from "vue";
</script>
