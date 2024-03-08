<script setup>
</script>

<template>
    <figure class="destiny-card">
        <div class="destiny-img">
            <img src="/places/one.jpg" alt="place">
        </div>
        <div class="destiny-info">
            <div class="destiny-main">
                <h3>Isla Mujeres, México</h3>
                <div class="destiny-score">
                    <img src="/icons/star.svg" alt="Star">
                    <span>4.99</span>
                </div>
            </div>
            <span>A 990 km de distancia</span>
            <span>19 - 24 de ene.</span>
            <span class="precio">
                <strong>$4,975 MXN</strong>
                noche
            </span>
        </div>
    </figure>
</template>

<style>
.destiny-card {
    width: 290px;
}

.destiny-img>img {
    border-radius: 16px;
    width: 290px;
    height: 290px;
}

.destiny-main {
    display: flex;
    align-items: center;
}

.destiny-main > h3 {
    margin-right: auto;
}

.destiny-score {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 4px;
}

.destiny-score > img {
    width: 12px;
}

.destiny-info {
    display: flex;
    flex-direction: column;
}

.destiny-info * {
    margin: 0;
    padding: 0;
}

.destiny-info > span {
    color: #717171;
}

.destiny-info > .precio {
    color: #000000;
}
</style>