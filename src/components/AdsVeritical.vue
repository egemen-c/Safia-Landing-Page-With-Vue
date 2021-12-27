<template >
    <section class="container">
        <div class="sub-large">READY TO START</div>
        <div class="h3-title"> Start your free trial today</div>
        <div><button class="button">Get Started <img src="@/assets/images/right-arrow.png" alt=""></button></div>
    </section>
</template>

<style scoped>
    .container{
        width: 65%;
        background-color:var(--blue-600);
        height: 350px;
        margin:  0 auto;
        margin-top: 100px;
        display: flex;
        flex-direction: column;
        flex-wrap: wrap;
        align-items: center;
        justify-content: space-evenly;
        border-radius: 27px;
    }
    .button{
        display: flex;
        align-items: center;
        background-color: var(--blue-300);
    }
</style>