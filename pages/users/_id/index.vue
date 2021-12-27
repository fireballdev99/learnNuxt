<template>
  <div>
    <h2>Welcome : {{ $route.params.id }}</h2>
  </div>
</template>
<script>
export default {
  validate(data) {
    return /^\d+$/.test(data.params.id);
  },
};
</script>