<template>
  <div>
    {{ listing.street }} {{ listing.street_nr }}, {{ listing.city }}, for
    ${{ listing.price }}
  </div>
</template>

<script setup>
defineProps({
  listing: Object,
})
</script>
