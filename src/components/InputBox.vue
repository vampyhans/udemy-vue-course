<template>
    <h1>Input Boxes</h1>

    <label for="cricket">Cricket</label>
    <input type="checkbox" name="cricket" v-model="sports" id="cricket" value="cricket">

    <label for="rugby">Rugby</label>
    <input type="checkbox" name="rugby" v-model="sports" id="rugby" value="rugby">

    <label for="chess">Chess</label>
    <input type="checkbox" name="chess" v-model="sports" id="chess" value="chess">

    <h3>Selected sport {{ sports }}</h3>



</template>
<script>
export default{
    name: "INPUTS",
    data (){
        return{
            sports : [],
        }
    }
};
</script>
<style scoped>
h1{
    color: gray;
}
h3{
    color: brown;
}
</style>