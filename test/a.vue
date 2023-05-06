<template>
  <div>
    <div v-for="item in list" :key="item.id">
      {{ item.name }}
    </div>
  </div>
</template>