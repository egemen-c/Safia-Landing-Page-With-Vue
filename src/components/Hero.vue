<template>
    <section class="container">
        <div class="col-1 hero-title">Landing Template for Startups</div>
        <div class="col-2">
            <span class="body-large">Our landing page template works on all devices, so you only have to set it up once,
                and get beautiful results forever.</span>
            <span><button class="button">Pricing and Plans</button></span>
        </div>
    </section>
</template>

<style scoped>
    .container {
        width: 100%;
        overflow: hidden;
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        gap: 20rem;
        margin-top:100px;
    }

    .body-large {
        color: var(--gray-500);
    }

    .button {
        background: #0059F7;
    }

    .col-2 {
        display: flex;
        flex-wrap: wrap;
        flex-direction: row;
        align-items: center;
        margin-right: 8rem;
    }

    .col-1 {
        margin-left: 8rem;
        display: flex;
        justify-content: center;
        align-items: center;
    }
</style>