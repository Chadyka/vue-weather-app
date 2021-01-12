<template>
  <div class="location-box">
    <div class="location">{{ city }}, {{ country }}</div>
    <div class="date">{{ date }}</div>
  </div>
</template>

<script>
export default {
  props: {
    city: String,
    country: String,
    date: String
  }
};
</script>

<style lang="scss">
.location-box .location {
  color: #fff;
  font-size: 32px;
  font-weight: 500;
  text-align: center;
  text-shadow: 1px 3px rgba(0, 0, 0, 0.25);
}
.location-box .date {
  color: #fff;
  font-size: 20px;
  font-weight: 300;
  font-style: italic;
  text-align: center;
}
</style>
