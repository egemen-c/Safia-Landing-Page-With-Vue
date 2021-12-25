<template>
    <section class="container">

        <img src="@/assets/images/google-logo.png" alt="google" class="col">
        <img src="@/assets/images/slack-logo.png" alt="slack" class="col">
        <img src="@/assets/images/amazon-logo.png" alt="amazon" class="col">
        <img src="@/assets/images/zoom-logo.png" alt="zoom" class="col">
        <img src="@/assets/images/netflix-logo.png" alt="netflix" class="col">
    
    </section>
</template>

<style scoped>
    .container{
        width: 80%;
        margin: 0 auto;
        margin-top: 80px;
        display: grid;
        grid-template-columns: repeat(5, 1fr);
        column-gap: 10px;
        justify-content: space-around;
        align-items: center;
    }
</style>