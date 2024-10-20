<template>
    <div>
        <HeaderComponent />
        <h2>If Else Page</h2>
        &nbsp;
        <FooterComponent />
    </div>
</template>

<script>
import HeaderComponent from '@/components/HeaderComponent.vue';
import FooterComponent from '@/components/FooterComponent.vue';

export default {
    name: 'IfElse',
    components: {
        HeaderComponent,
        FooterComponent,
    }
};
</script>

<style scoped>
h2 {
    color: #42b983;
}
</style>