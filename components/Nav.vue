<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark padding">
    <!-- <a class="navbar-brand" href="/"> Firengii</a> -->
    <button
      class="button--green"
      type="button"
      data-toggle="collapse"
      data-target="#navbarSupportedContent"
      aria-controls="navbarSupportedContent"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      Home <span class="navbar-toggler-icon"></span>
    </button>
    <a href="/products" class="button--green"
      >Products <span class="sr-only">(current)</span></a
    >
    <a href="/About" class="button--green"
      >About <span class="sr-only">(current)</span></a
    >
  </nav>
</template>

<script>
export default {}
</script>

<style scoped>
.padding {
  padding: 1.5rem;
  background-color: whitesmoke;
}
.nav-left {
  margin-left: auto;
}
.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}
</style>
