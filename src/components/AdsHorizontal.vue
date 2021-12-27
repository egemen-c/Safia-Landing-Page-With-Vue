<template>
  <section class="container">
    <div class="col">
      <div class="sub-large">READY TO START</div>
      <div class="h3-title">Start your free trial today</div>
    </div>
    <div class="col">
      <div>
        <button class="button">
          Get Started <img src="@/assets/images/right-arrow.png" alt="" />
        </button>
      </div>
    </div>
  </section>
</template>

<style scoped>
.container {
  width: 80%;
  border-radius: 16px;
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  background-color: var(--blue-600);
  margin: 0 auto;
  margin-top: 100px;
  align-items: center;
  justify-content: flex-end;
  padding: 70px;
}
.button {
  float: right;
  display: flex;
  align-items: center;
  background: var(--blue-300);
}
</style>
