<template>
    <div class="todo container">
        <div class="jumbotron-fluid leading-message">
            <h1>Hello Jake</h1>
            <p class="lead">Let's get our schedule updated and 
                planned out so the day can flow much more smooth.
            </p>
        </div>
    </div>
</template>

<script>
export default {
    name: 'todos',

};
</script>

<style>
    .todo {
        text-align: center;
    }

    .lead {
        padding-top: 20px;
        width: 40%;
        margin: 0 auto;
        font-family: "Montserrat";
       font-weight: 100;
        line-height: 1.5;
    }

    .leading-message {
        margin-top: 10%;
    }
</style>
