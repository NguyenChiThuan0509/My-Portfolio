<script></script>

<template>

    <div class="header">
        <a href="#home">Home</a>
        <a href="#project">Project</a>
        <a href="#contact">Contact</a>
    </div>

</template>

<style>
.header {
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 20px;
    background-color: rgba(253, 48, 4, 0.8);
    border-radius: 20px;
    margin: 20px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.header a {
    text-decoration: none;
    color: #333;
    font-weight: bolder;
    font-size: larger;
    padding: 10px 20px;
}

.header a:hover {
    background-color: #ddd;
    border-radius: 10px;
}
</style>