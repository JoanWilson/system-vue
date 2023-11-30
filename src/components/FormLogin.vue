<script>
import FormInput from './FormInput.vue';

export default {
  components: {
    FormInput
  }
}
</script>

<template>
  <form class="max-w-sm mx-auto h-full flex flex-col justify-center">
    <form-input label="Email" type="email" placeholder="Your email" required />
    <form-input label="Password" type="password" placeholder="Your password" required />
    <div class="flex items-start mb-5">
      <div class="flex items-center h-5">
        <input id="remember" type="checkbox" value=""
          class="w-4 h-4 border border-gray-300 rounded bg-gray-50 focus:ring-3 focus:ring-blue-300 dark:bg-gray-700 dark:border-gray-600 dark:focus:ring-blue-600 dark:ring-offset-gray-800 dark:focus:ring-offset-gray-800"
          required>
      </div>
      <label for="remember" class="ms-2 text-sm font-medium text-gray-900 dark:text-gray-300">Remember me</label>
    </div>
    <button type="submit"
      class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm w-full sm:w-auto px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">Submit</button>
  </form>
</template>