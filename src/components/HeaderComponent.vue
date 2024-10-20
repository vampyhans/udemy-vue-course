<template>
    <header>
        <nav class="navbar">
            <ul>
                <li>Vue Udemy Course</li>
                <li><router-link to="/">Home</router-link></li>
                <li><router-link to="/if-else">IfElse</router-link></li>
            </ul>
        </nav>
    </header>
</template>

<script>
export default {
    name: 'HeaderComponent'
};
</script>

<style scoped>
.navbar {
    background-color: #42b983;
    padding: 1rem;
}

.navbar ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content:flex-start;
}

.navbar ul li {
    margin: 0 1rem;
}

.navbar ul li a {
    color: white;
    text-decoration: none;
    font-size: 1.2rem;
}

.navbar ul li a:hover {
    text-decoration: underline;
}
</style>