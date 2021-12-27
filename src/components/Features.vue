<template>
  <section class="container">
    <div class="col">
      <div class="icon"><img src="@/assets/images/dashboard-icon.png" alt="" /></div>
      <div class="h4-title">Dashboard</div>
      <div class="body-default">
        A pseudo-Latin text used in web design, layout, and printing in place of things to
        emphasise layouts for previewing layouts and visual mockups.
      </div>
    </div>
    <div class="col">
      <div class="icon"><img src="@/assets/images/comment-icon.png" alt="" /></div>
      <div class="h4-title">Comment</div>
      <div class="body-default">
        A pseudo-Latin text used in web design, layout, and printing in place of things to
        emphasise layouts for previewing layouts and visual mockups.
      </div>
    </div>
    <div class="col">
      <div class="icon"><img src="@/assets/images/tailored-icon.png" alt="" /></div>
      <div class="h4-title">Tailored Comments</div>
      <div class="body-default">
        A pseudo-Latin text used in web design, layout, and printing in place of things to
        emphasise layouts for previewing layouts and visual mockups.
      </div>
    </div>
    <div class="col">
      <div class="icon"><img src="@/assets/images/statics-icon.png" alt="" /></div>
      <div class="h4-title">Statics</div>
      <div class="body-default">
        A pseudo-Latin text used in web design, layout, and printing in place of things to
        emphasise layouts for previewing layouts and visual mockups.
      </div>
    </div>
    <div class="col">
      <div class="icon"><img src="@/assets/images/profiles-icon.png" alt="" /></div>
      <div class="h4-title">Profiles</div>
      <div class="body-default">
        A pseudo-Latin text used in web design, layout, and printing in place of things to
        emphasise layouts for previewing layouts and visual mockups.
      </div>
    </div>
    <div class="col">
      <div class="icon"><img src="@/assets/images/folders-icon.png" alt="" /></div>
      <div class="h4-title">Folders</div>
      <div class="body-default">
        A pseudo-Latin text used in web design, layout, and printing in place of things to
        emphasise layouts for previewing layouts and visual mockups.
      </div>
    </div>
  </section>
</template>
<style scoped>
.container {
  width: 65%;
  margin: 0 auto;
  margin-top: 100px;
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-template-rows: repeat(3, 1fr);
  gap: 40px;
}
.col {
  border: 0.5px solid rgba(78, 90, 133, 0.3);
  border-radius: 8px;
}
.col div {
  padding: 15px;
}
</style>
