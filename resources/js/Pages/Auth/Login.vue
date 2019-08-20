<template>
    <auth>
        <h1 class="font-bold text-gray-600 text-center text-2xl mb-4">
            Đăng Nhập
        </h1>

        <div class="mb-4">
            <label class="block font-bold text-gray-600 mb-1" for="username">
                Tên đăng nhập
            </label>

            <input class="form-input" placeholder="Tên đăng nhập, email, SĐT..." autocomplete="username" autofocus id="username" name="username" required type="text">
        </div>
    </auth>
</template>

<script>
  import Auth from '../../Layouts/Auth.vue';

  export default {
    components: {
      Auth
    }
  };
</script>
