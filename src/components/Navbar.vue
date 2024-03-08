<script setup>
</script>

<template>
    <header>
        <img src="/logo.svg" alt="airbnb" title="airbnb">
        <div class="time-details">
            <span>Cualquier lugar</span>
            <hr>
            <span>Cualquier semana</span>
            <hr>
            <span>¿Cuántos?</span>
            <img src="/icons/search.svg" alt="search">
        </div>
        <span>Hazte anfitrión</span>
        <img src="/icons/language.svg" alt="language">
        <button class="user-button">
            <img src="/icons/menu.svg" alt="menu">
            <img src="/icons/user.svg" alt="user">
        </button>
    </header>
</template>

<style scoped>
header {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 80px;
    padding: 20px 0;
}
header * {
    margin: 0 auto;
}
.time-details {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 8px 8px 8px 24px;
    border: 1px solid #EBEBEB;
    border-radius: 40px;
    gap: 59px;
}

.time-details hr {
    width: 20px;
    color: #EBEBEB;
    transform: rotate(90deg);
}
.time-details img {
    padding: 8px;
    border-radius: 50%;
    background-color: #FF385C;
    color: white;
}

.user-button {
    display: flex;
    border: 1px solid #EBEBEB;
    border-radius: 40px;
    padding: 8px 8px 8px 16px;
    gap: 16px;
    background-color: white;
}
</style>