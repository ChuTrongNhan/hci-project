<template>
  <div>
    <TravelMap class="travel-map"/>
  </div>
</template>

<script>
import TravelMap from "@/components/Map";

export default {
  name: "Map",
  components: {
    TravelMap
  }
};
</script>

<style lang="scss" scoped>
.travel-map {
  height: 400px;
}
</style>

