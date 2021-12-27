<template>
  <div class="title-wrap">
    <span class="sub-large">Saflow</span>
    <span class="h2-title">How does it work?</span>
  </div>
  <section class="container">
    <div class="row">
      <div class="col">
        <img src="@/assets/images/Saflow-row-item.png" alt="" />
      </div>
      <div class="col">
        <div class="h3-title">How does it work?</div>
        <div class="body-large">
          Our landing page template works on all devices, so you only have to set it up
          once, and get beautiful results.
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col">
        <div class="h3-title">How does it work?</div>
        <div class="body-large">
          Our landing page template works on all devices, so you only have to set it up
          once, and get beautiful results.
        </div>
      </div>
      <div class="col">
        <img src="@/assets/images/Saflow-row-item.png" alt="" />
      </div>
    </div>
    <div class="row">
      <div class="col">
        <img src="@/assets/images/Saflow-row-item.png" alt="" />
      </div>
      <div class="col">
        <div class="h3-title">How does it work?</div>
        <div class="body-large">
          Our landing page template works on all devices, so you only have to set it up
          once, and get beautiful results.
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.container {
  width: 80%;
  margin: 0 auto;
  margin-top: 100px;
  display: grid;
  grid-template-rows: repeat(3, 1fr);
  align-items: center;
  justify-content: center;
}
.row {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 40px;
  align-items: center;
  justify-content: center;
  margin-bottom: 60px;
}
.title-wrap {
  width: 80%;
  margin: 0 auto;
  align-items: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
  margin-top: 100px;
  margin-bottom: 100px;
}
</style>
