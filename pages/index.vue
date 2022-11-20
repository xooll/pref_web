<template>
  <div class="bg-gray-50 dark:bg-gray-900 h-screen">
    <span class="text-gray-900 dark:text-white text-lg" >Преферанс</span>
    <div>
      <label
        for="email"
        class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
        >E-mail</label
      >
      <input
        type="text"
        id="email"
        class="
          bg-gray-50
          border border-gray-300
          text-gray-900 text-sm
          rounded-lg
          focus:ring-blue-500 focus:border-blue-500
          block
          w-full
          p-2.5
          dark:bg-gray-700
          dark:border-gray-600
          dark:placeholder-gray-400
          dark:text-white
          dark:focus:ring-blue-500
          dark:focus:border-blue-500
        "
        placeholder="email@domain.com"
        required
      />
    </div>
  </div>
</template>

<script>
export default {
  name: "Главная",
};
</script>
