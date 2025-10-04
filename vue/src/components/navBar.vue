<script setup>
</script>

<template>
    <header>
        <nav class="navbar">
            <div class="logo">Eduo.</div>
            <ul class="nav-links">
                <li><a href="#">Court List</a></li>
                <li><a href="#">Innovations</a></li>
                <li><a href="#">Platform</a></li>
                <li><a href="#">Resources</a></li>
            </ul>
            <button class="btn-primary">Request Demo</button>
        </nav>
    </header>
</template>

<style scoped>
        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: #2b00ff;
            padding: 1.25em 2em;
            color: #fff;
        }

        .logo {
            font-weight: bold;
            font-size: 1.5em;
        }

        .nav-links {
            list-style: none;
            display: flex;
            gap: 2em;
        }

        .nav-links li a {
            color: #fff;
            text-decoration: none;
            font-weight: 500;
        }

        .btn-primary {
            background: #2b00ff;
            color: #fff;
            border: none;
            border-radius: 6px;
            padding: 0.6em 1.4em;
            cursor: pointer;
        }
</style>