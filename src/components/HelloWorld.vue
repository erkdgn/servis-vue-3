<template>
  <div class="container">
    <div class="card">
      <div class="card-body">
        <h1>{{ msg }}</h1>
        <h3>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Perferendis,
          sint.
        </h3>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>
