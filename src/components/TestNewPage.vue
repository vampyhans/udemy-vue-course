<template>
    <h1>Hello There {{ getName('Trump') }}</h1>
    <h2>Your email is {{ email }}</h2>
    <button v-on:click="onClick()">On Click</button>
</template>
<script>
export default{
    name: "PAGES",
    data (){
        return{
            email: "test@example.com",
        };
    },
    methods: {
        getName(name) {
            return name;
        },
        onClick(){
            alert('On click');
        }
    }
}
</script>
<style scoped>

</style>