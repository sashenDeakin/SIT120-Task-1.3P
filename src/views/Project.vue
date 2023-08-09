<script setup>
import { ref } from "vue";

const itemsID = ref(0);
const shoppingItems = ref("");
const store = ref([]);
const shopped = ref(false);

function addItems() {
  store.value.push({
    id: itemsID.value++,
    items: shoppingItems.value,
    status: shopped.value,
  });

  console.log(store.value.flat());

  shoppingItems.value = "";
}
</script>

<template>
  <div class="about">
    This is my project page

    <input type="text" v-model="shoppingItems" />
    <button @click="addItems">Add Items</button>

    <ol>
      <li v-for="i in store">
        {{ i.items }}
        <button>X</button>
      </li>
      <h5 v-if="store.length < 1">no Items</h5>
    </ol>
  </div>
</template>

<style>
.about {
  font-size: 50px;
}

@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
