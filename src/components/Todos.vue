<template>
  <div>
    <h2>{{ count }}</h2>
    <button @click="increaseCount">Change</button>
  </div>
</template>

<script>
export default {
  name: "Todos",
  data() {
    return {
      count: 0,
    };
  },

  methods: {
    increaseCount: function() {
      this.count += 1;
    },
  },
};
</script>
