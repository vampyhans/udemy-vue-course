<template>
    <h1>Two Way Binding</h1>
    <input type="number" name="number" id="number" placeholder="add a number" v-model="count">
    <h2>{{ count }}</h2>
</template>
<script>
export default{
    name: "TWO_WAY_BINDING",
    data(){
        return {
            count : 0
        };
    },
};
</script>
<style scoped>
h1{
    color: blue;
}
</style>