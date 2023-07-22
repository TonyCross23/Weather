<template>
  <div>
    <Suspense>
      <AsyncCityView />
      <template #fallback>
        <p>Loading...</p>
      </template>
    </Suspense>
  </div>
</template>

<script setup>
import AsyncCityView from "../components/AsyncCityView.vue";

name: {
  ("CityView");
}
</script>
