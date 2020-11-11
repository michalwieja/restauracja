<template>
  <div>
    <div class="pageTitle">Cennik</div>
    <div class="wrapper">
      <p>
        Każda pizza na włoskim, cienkim cieście drożdżowym z sosem pomidorowym,
        serem mozzarella, z dodatkiem składników najwyższej jakości, doprawiana
        solą i oregano. Średnia 28 cm/ duża 38 cm
      </p>
      <PriceListItem name="przystawki" />
      <PriceListItem name="pizza" />
      <PriceListItem name="salatki" />
      <PriceListItem name="przystawki" />
    </div>
  </div>
</template>

<script>
import PriceListItem from "@/components/PriceListItem";
export default {
  components: {
    PriceListItem,
  },
  props: {
    name: { type: String, required: false },
  },
};
</script>

<style scoped lang='scss'>
.wrapper {
  margin-top: 10vh;
}
</style>