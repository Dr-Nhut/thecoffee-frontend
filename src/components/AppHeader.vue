<template>
    <div class = "over">
        <nav class="navbar navbar-expand navbar-dark navbar-css">
        <a href="/" class="navbar-brand">Cafe Management App</a>
        <div class="mr-auto navbar-nav  navbar-nav-css">
            <li class="nav-item">
                <router-link :to="{ name: 'home' }" class="nav-link-css">
                    <i class="fa-solid fa-house"></i>
                    Trang chủ
                </router-link>
            </li>
        </div>
    </nav>
    </div>
</template>

<style>
    .over {
        background-color: green;
    }
    .navbar-css {
        max-width: 1200px;
        margin-left: auto;
        margin-right: auto;
    }

    .navbar-nav-css {
        margin-left: 50px;
    }

    .nav-link-css {
        font-size: 16px;
        color: #fff;
    }

    .nav-link-css:hover {
        color: #ccc;
        text-decoration: none;
    }

    .nav-link-css i {
        margin-right: 4px;
    }
</style>