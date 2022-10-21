<template>
<header>
    <h1 class="title">Welcome to <br> My Portofolio Website</h1>
    <nav id = "navigation">
        <RouterLink :to = "{ name: 'home' }">Homepage</RouterLink>
        <RouterLink :to = "{ name: 'about' }">About</RouterLink>
    </nav>
</header>
</template>

<style lang ="scss" >
#navigation {
    display : flex;
    gap : 1rem;
    text-align: center;
}

.title {
    text-align: center;
}
</style>