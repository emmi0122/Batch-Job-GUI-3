<template>
    <nav class="sidebar">
        <div class="sidebar-logo">
            <!-- <img src="Assets/avatar.png" alt="Logo of company"> -->
            <span class="logo-text">T</span>
        </div>

        <ul class="sidebar-menu">
            <li><span class="icon"><i class="fas fa-search"></i></span></li>
            <li><span class="icon"><i class="fas fa-home"></i></span></li>
            <li><span class="icon"><i class="fas fa-users"></i></span></li>
            <li><span class="icon"><i class="fas fa-clock"></i></span></li>
            <li><span class="icon"><i class="fas fa-briefcase"></i></span></li>
        </ul>

        <div class="sidebar-bottom">
            <span class="icon"><i class="fas fa moon"></i></span>
        </div>
    </nav>
</template>

<style scoped>
.sidebar {
    width: 70px;
    background: #f8f9fc;
    height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    border-right: 1px solid #e0e0e0;
    position: fixed;
    top: 0;
    left: 0;
    z-index: 100;
}

.sidebar-logo {
    margin: 24px 0 24px 0;
}

.logo-text {
    font-size: 2.2rem;
    font-weight: bold;
    color: #22356f;
    background: #e3eafc;
    border-radius: 50%;
    width: 48px;
    height: 48px;
    display: flex;
    align-items: center;
    justify-self: center;
}

.sidebar-menu {
    list-style: none;
    padding: 0;
    margin: 0;
    flex: 1;
    display: flex;
    flex-direction: column;
    gap: 24px;
}

.sidebar-menu li {
    width: 100%;
    display: flex;
    justify-content:  center;
}

.icon {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 40px;
    height: 40px;
    font-size: 1.5rem;
    color: #22356f;
    border-radius: 12px;
}

.icon:hover {
    background: #e3eafc;
}

.sidebar-botton {
    margin-bottom: 24px;
}

.sidebar-bottom .icon {
    font-size: 1.7rem;
}
</style>