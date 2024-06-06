<script setup>
const { t } = useI18n()
</script>
<template>
  <div class="text-lg mx-auto max-w-6xl">
    <h1 class="font-bold text-2xl my-8">{{ t("home.welcome") }}</h1>
    <p v-html="t('home.description')"></p>

    <h2 class="font-bold text-xl my-4">{{ t('home.history') }}</h2>

    <ul class="list-decimal list-inside">
      <li>
        {{ t('home.v101') }} {{ t('home.v101_date') }}
        <ul class="list-disc list-inside ml-4">
          <li v-html="t('home.v101_1')"></li>
          <li v-html="t('home.v101_2')"></li>
          <li v-html="t('home.v101_3')"></li>
          <li v-html="t('home.v101_4')"></li>
        </ul>
      </li>
    </ul>
  </div>
</template>
