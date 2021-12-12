<template>
  <Link
    class="w-full hover:underline font-thin uppercase text-gray-500 dark:text-gray-200 flex items-center p-4 my-2 transition-colors duration-200 justify-start hover:text-blue-500"
    :class="{'w-full hover:underline font-thin uppercase text-blue-500 flex items-center p-4 my-2 transition-colors duration-200 justify-start bg-gradient-to-r from-white to-blue-100 border-r-4 border-blue-500 dark:from-gray-700 dark:to-gray-800 border-r-4 border-blue-500': active }"
  >
    <slot />
  </Link>
</template>

<script>
export default {
  props: {
    active: Boolean
  }
};
</script>
