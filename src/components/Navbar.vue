<template>
    <section class="container">
        <div class="logo">
            <img src="@/assets/images/safia-logo-light.svg" alt="">
        </div>
        <div class="login">
            <button class="button">Login</button>
        </div>
    </section> 

</template>

<style scoped>
    .container {
        width: 100%;
        background-color: var(--gray-900);
        height: 100px;
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        border-bottom: 0.5px solid rgba(78, 90, 133, 0.3);
    }

    .logo {
        padding-left: 30px;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }

    .login {
        padding-right: 30px;
        display: flex;
        flex-direction: row-reverse;
        align-items: center;
        justify-content: space-between;
    }

    .login>button {
        background-color: var(--gray-700);
        color: #fff;
        width: 94px;
        height: 56px;
        padding: 16px 24px;
        border: none;
        border: 0px solid var(--gray-700);
        border-radius: 8px;
    }
</style>