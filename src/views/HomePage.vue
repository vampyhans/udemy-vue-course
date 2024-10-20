<template>
    <div>
        <HeaderComponent />
        <h2>Home Page</h2>
        &nbsp;
        <TestNewPage />
        <InputBox />
        <TwoWayBinding />
        <FooterComponent />
    </div>
</template>

<script>
import HeaderComponent from '@/components/HeaderComponent.vue';
import FooterComponent from '@/components/FooterComponent.vue';
import TestNewPage from '@/components/TestNewPage.vue';
import InputBox from '@/components/InputBox.vue';
import TwoWayBinding from '@/components/TwoWayBinding.vue';

export default {
    name: 'HomePage',
    components: {
        HeaderComponent,
        FooterComponent,
        TestNewPage,
        InputBox,
        TwoWayBinding
    }
};
</script>

<style scoped>
h2 {
    color: #42b983;
}
</style>