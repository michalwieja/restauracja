<template>
  <div>
    <div class="item">
      <div class="name">{{ name }}</div>
      <button @click="showItems()">Rozwin</button>
    </div>
    <div class="items" v-show="open">
      <ul>
        <li v-for="item in items" :key="item">{{ item }}</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "PriceListItem",
  data() {
    return {
      open: false,
      items: ["frytki", "pizza", "burger"],
    };
  },
  methods: {
    showItems() {
      this.open = !this.open;
    },
  },
  props: ["name"],
};
</script>

<style lang='scss' scoped>
.item {
  margin-top: 5vh;
  display: flex;
  width: 100%;
  align-items: center;
  justify-content: space-between;
  padding: 10px;
  border-radius: 10px;
  box-shadow: 5px 5px 20px $light-grey;
  button {
    height: 54px;
    width: 162px;
  }
}

.items {
  margin-top: 5vh;
  ul {
    list-style: none;
    li {
      padding: 10px;
    }
  }
}
</style>