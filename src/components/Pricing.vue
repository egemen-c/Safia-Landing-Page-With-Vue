<template>
  <div class="title-wrap">
    <span class="sub-large">Saflow</span>
    <span class="h2-title">Pricing</span>
  </div>
  <section class="container">
    <div>
      <div class="top-container bottom-border">
        <div class="sub-large">FREE</div>
        <div class="h1-title"><span class="dollar">$</span>0</div>
      </div>
      <div>
        <ul class="body-default">
          <li><img src="@/assets/images/tick-icon.png" alt="" /> 7,000,000+ Events</li>
          <li><img src="@/assets/images/tick-icon.png" alt="" />4 Custom Domains</li>
          <li>
            <img src="@/assets/images/tick-icon.png" alt="" />Dedicated Support Agent
          </li>
          <li>
            <img src="@/assets/images/tick-icon.png" alt="" />12 Months Data History
          </li>
          <li><img src="@/assets/images/tick-icon.png" alt="" />1 Dedicated SSL</li>
          <li>
            <button class="button">
              Get Started <img src="@/assets/images/right-arrow.png" alt="" />
            </button>
          </li>
        </ul>
      </div>
    </div>
    <div>
      <div class="top-container bottom-border">
        <div class="sub-large">BASIC</div>
        <div class="h1-title"><span class="dollar">$</span>0</div>
      </div>
      <div>
        <ul class="body-default">
          <li><img src="@/assets/images/tick-icon.png" alt="" /> 7,000,000+ Events</li>
          <li><img src="@/assets/images/tick-icon.png" alt="" />4 Custom Domains</li>
          <li>
            <img src="@/assets/images/tick-icon.png" alt="" />Dedicated Support Agent
          </li>
          <li>
            <img src="@/assets/images/tick-icon.png" alt="" />12 Months Data History
          </li>
          <li><img src="@/assets/images/tick-icon.png" alt="" />1 Dedicated SSL</li>
          <li>
            <button class="button">
              Get Started <img src="@/assets/images/right-arrow.png" alt="" />
            </button>
          </li>
        </ul>
      </div>
    </div>
    <div>
      <div class="top-container bottom-border">
        <div class="sub-large">PREMIMUM</div>
        <div class="h1-title"><span class="dollar">$</span>0</div>
      </div>
      <div>
        <ul class="body-default">
          <li><img src="@/assets/images/tick-icon.png" alt="" /> 7,000,000+ Events</li>
          <li><img src="@/assets/images/tick-icon.png" alt="" />4 Custom Domains</li>
          <li>
            <img src="@/assets/images/tick-icon.png" alt="" />Dedicated Support Agent
          </li>
          <li>
            <img src="@/assets/images/tick-icon.png" alt="" />12 Months Data History
          </li>
          <li><img src="@/assets/images/tick-icon.png" alt="" />1 Dedicated SSL</li>
          <li>
            <button class="button">
              Get Started <img src="@/assets/images/right-arrow.png" alt="" />
            </button>
          </li>
        </ul>
      </div>
    </div>
  </section>
</template>

<style scoped>
ul li {
  list-style-type: none;
  display: flex;
  align-items: center;
  justify-content: start;
  padding-bottom: 15px;
}
.container {
  margin: 0 auto;
  width: 90%;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 50px;
}

.container > div {
  background-color: var(--gray-800);
  border-radius: 10px;
}

.top-container {
  width: 80%;
  display: flex;
  align-items: start;
  flex-direction: column;
  flex-wrap: wrap;
  justify-content: center;
  height: 200px;
  margin: 0 auto;
}

.dollar {
  color: var(--gray-600) !important;
}

.button {
  display: flex;
  align-items: center;
  background: var(--blue-300);
  margin-top: 50px;
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
