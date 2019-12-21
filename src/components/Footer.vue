<template>
  <div class="text-center mt-2 footer">
    <hr class="borderBot" />
    <div class="row">
      <div class="col col-md-4">
        <h2 class="mt-4">&copy; 2019 D3 TECH</h2>
      </div>
      <div class="col col-md-4">
        <div class="cart">
          <i class="fas fa-shopping-cart btnCart"></i>
        </div>
      </div>

      <div class="col col-md-4">
        <h2 class="mt-4">&copy; 2019 D3 TECH</h2>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.footer {
  position: relative;
  width: 100%;
  height: 4rem;
}

.borderBot {
  margin: 0 auto;
  width: 80%;
  border: 1px solid rgb(14, 13, 13);
}
div h2 {
  font-family: "Share Tech Mono", monospace;
  color: #0ccac4;
  font-weight: 400;
  font-size: 25px;
}

.cart {
  /* position: relative; */
  left: 50%;
  transform: translateX(-50%);
  background: #071b52;
  height: 3rem;
  width: 10rem;
  position: fixed;
  bottom: 0;
  text-align: center;
}

.btnCart {
  margin: 15px auto;
  font-size: 25px;
  color: #0ccac4;
}
</style>