<template>
  <div>
    <p>{{copyright}}</p>
  </div>
</template>

<script>
export default {
  name: "FooterCustom",
  data() {
    return {
      copyright: "Brais Montáns Bouza, 2020-2021"
    };
  }
};
</script>

<style scoped>
p {
  font-size: 0.8rem;
}
</style>