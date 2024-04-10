<template>
    <v-layout class="rounded rounded-md">
      <v-app-bar color="surface-variant" title="Proud App"></v-app-bar>
      <v-main class="w-100 d-flex align-center justify-center" style="min-height: 300px;">
        <Form />
      </v-main>
    </v-layout>
</template>

<script setup>
    import Form from './Form/Form.vue';
</script>