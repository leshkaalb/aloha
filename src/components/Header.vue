<template>
    <header class="header">
        <div class="header-container">
            <nav class="nav-menu">
                <ul class="nav-list">
                    <li class="nav-item">
                        <a href="#" class="nav-link">About Us</a>
                    </li>
                    <li class="nav-item">
                        <a href="#" class="nav-link">Service</a>
                    </li>
                    <li class="nav-item">
                        <a href="#" class="nav-link">Menu</a>
                    </li>
                    <li class="nav-item">
                        <a href="#" class="nav-link">Contact</a>
                    </li>
                </ul>
            </nav>
            <div class="logo">
                <img src="../assets/logo.svg" alt="Logo" class="logo-image">
            </div>
            
            <div class="header-actions">
                <button class="search-btn" @click="handleSearch">
                    <svg class="search-icon" width="20" height="20" viewBox="0 0 24 24" fill="none">
                        <path d="M21 21L16.514 16.506L21 21ZM19 10.5C19 15.194 15.194 19 10.5 19C5.806 19 2 15.194 2 10.5C2 5.806 5.806 2 10.5 2C15.194 2 19 5.806 19 10.5Z" 
                            stroke="currentColor" stroke-width="2" stroke-linecap="round"/>
                    </svg>
                </button>
                
                <button class="register-btn">
                    Regestar Now
                </button>
            </div>
        </div>
    </header>
</template>

<script setup>
const handleSearch = () => {
    console.log('Search clicked');
};
</script>

<style scoped>
.header {
    width: 100%;
    background: #fff;
    padding: 48px 0;
}

.header-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1240px;
    width: 100%;
    margin: 0 auto;
    padding: 0 20px;
    position: relative;
}

.nav-list {
    display: flex;
    list-style: none;
    gap: 2rem;
    margin: 0;
    padding: 0;
}

.nav-link {
    text-decoration: none;
    color: #333;
    font-weight: 500;
    transition: color 0.3s ease;
    font-size: 18px;
}

.nav-link:hover {
    color: #007bff;
}

.logo {
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
}

.logo-image {
    height: 56px; 
    width: 56px;
}

.header-actions {
    display: flex;
    align-items: center;
    gap: 1rem;
}

.search-btn {
    background: none;
    border: none;
    cursor: pointer;
    padding: 0.5rem;
    color: #333;
    transition: color 0.3s ease;
    display: flex;
    align-items: center;
    justify-content: center;
}

.search-btn:hover {
    color: #007bff;
}

.register-btn {
    background-color: #09A66D;
    color: white;
    border: none;
    padding: 12px 24px;
    border-radius: 5px;
    cursor: pointer;
    font-weight: 500;
    transition: background-color 0.3s ease;
    font-size: 16px;
}

.register-btn:hover {
    background-color: #078857;
}

/* Адаптивность */
@media (max-width: 768px) {
    .header-container {
        flex-wrap: wrap;
        justify-content: center;
        gap: 1rem;
    }
    
    .logo {
        position: static;
        transform: none;
        order: -1;
    }
    
    .nav-menu {
        order: 1;
    }
    
    .header-actions {
        order: 2;
    }
}
</style>