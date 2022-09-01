<template>
  <div>
    <div class="mx-auto text-center">
      <div>
        <img :src="item.image" alt="" class="border border-gray p-5" />
      </div>
      <h4 class="font-oswald uppercase text-2xl mt-5 text-black dark:text-gray-100">
        {{ item.name }}
      </h4>
      <p class="font-light text-gray-500 dark:text-gray-300 my-2">
        {{ item.description }}
      </p>
    </div>
  </div>
</template>

<script>
export default {
  props: ['item'],
};
</script>
