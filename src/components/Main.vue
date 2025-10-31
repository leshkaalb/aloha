<template>
    <main class="main">
        <img class="leaf-left" src="../assets/listok.png" alt="Leaf decoration">
        <div class="container">
            <div class="content">
                <div class="main-content">
                    <h1 class="title">Organic Fruit & Vegetables</h1>
                    <p class="description">
                        Lorem Ipsum is simply dummy text of the printing and typesetting industry.  
                        Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, 
                        when an unknown printer took a galley...
                    </p>
                    <div class="order-btn">
                        Order Now
                        <img src="" alt="">
                    </div>
                    
                    <div class="stats">
                        <img class="vegetables__img" src="../assets/vegetables.png"> 
                        <div class="stat-item">
                            <div class="stat-number">30K</div>
                            <div class="stat-label">User Order</div>
                        </div>
                        <div class="stat-item">
                            <div class="stat-number">20K</div>
                            <div class="stat-label">Reviews(4.8)</div>
                        </div>
                        <div class="stat-item">
                            <div class="stat-number">300</div>
                            <div class="stat-label">Items</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </main>
</template>

<script setup>

</script>

<style scoped>
.container {
    background-color: #F3FBF8;
    width: 100%;
    margin: 0 auto;
    padding: 92px 20px;
}
.leaf-left {
    position: absolute;
    left: 250px;
    top: 103px;
}

.main-content {
    text-align: center;
    margin: 0 auto;
    position: relative;
    z-index: 2;
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
    margin-bottom: 32px;
    max-width: 40rem;
    margin-left: auto;
    margin-right: auto;
}

.order-btn {
    padding: 16px 32px;
    font-size: 18px;
    cursor: pointer;
    margin-bottom: 60px;
}


.stats {
    display: flex;
    justify-content: center;
    gap: 60px;
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