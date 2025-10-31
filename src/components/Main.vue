<template>
    <main class="main">
        <div class="container">
            <div class="content">
                <h1 class="title">Organic Fruit & Vegetables</h1>
                <p class="description">
                    Lorem Ipsum is simply dummy text of the printing and typesetting industry.  
                    Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, 
                    when an unknown printer took a galley...
                </p>
                </div>
            </div>
    </main>
</template>

<script setup>
</script>

<style scoped>
.main {
    width: 100%;
    background-color: #F3FBF8;
    margin-top: 20px;
}

.container {
    max-width: 1240px;
    width: 100%;
    margin: 0 auto;
    padding: 92px 20px;
    display: flex;
    align-items: center;
    justify-content: center;
}

.content {
    text-align: center;
}

.title {
    font-size: 70px;
    font-weight: bold;
    color: #333;
    margin-bottom: 24px;

}

.description {
    font-size: 18px;
    color: #666;
    line-height: 1.6;
    margin-bottom: 32px;
    max-width: 500px;
    margin-left: auto;
    margin-right: auto;
}

.order-btn {
    background-color: #09A66D;
    color: white;
    border: none;
    padding: 16px 32px;
    border-radius: 8px;
    font-size: 18px;
    font-weight: 600;
    cursor: pointer;
    transition: background-color 0.3s ease;
    margin-bottom: 60px;
}

.order-btn:hover {
    background-color: #078857;
}

.stats {
    display: flex;
    justify-content: center;
    gap: 60px;
    margin-top: 40px;
}

.stat-item {
    text-align: center;
}

.stat-number {
    font-size: 32px;
    font-weight: bold;
    color: #333;
    margin-bottom: 8px;
}

.stat-label {
    font-size: 16px;
    color: #666;
}

</style>