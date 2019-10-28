<template>
  <div class="col-sm-6">
    <div class="panel panel-default">
      <div class="panel-body quote">
        <slot></slot>
      </div>
    </div>
  </div>
</template>

<script>
</script>

<style scoped>
.panel-body {
  font-family: "Arizonia", cursive;
  font-size: 24px;
  color: gray;
}
.quote {
  cursor: pointer;
}

.quote:hover {
  background-color: lightcoral;
}
</style>