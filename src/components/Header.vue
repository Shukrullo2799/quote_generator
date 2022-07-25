<template>
  <header>
    <h1>{{ title }}</h1>
  </header>
</template>

<script>
export default {
  name: "HeaderQuote",
  props: {
    title: {
      type: String,
    },
  },
};
</script>

<style lang="scss" scoped>
header {
  padding: 24px 32px;
  display: flex;
  justify-content: center;

  h1 {
    font-size: 32px;
    font-weight: 700;
    color: var(--dark);
    text-align: center;
    text-transform: uppercase;
    border-bottom: 5px solid var(--primary);
  }
}
</style>
