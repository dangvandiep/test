<template>
    <app class="text-center">
        <h1 class="font-bold text-xl text-gray-500">
            Welcome
        </h1>

        <span class="mb-4">
            Welcome to your app! - <inertia-link class="text-blue-500" href="/test">Move to test page</inertia-link>
        </span>
    </app>
</template>

<script>
  import App from '../Layouts/App.vue';

  export default {
    components: {
      App
    }
  };
</script>
