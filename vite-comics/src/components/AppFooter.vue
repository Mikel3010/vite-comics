<script>

import AppFooterTop from './AppFooterTop.vue';
import AppFooterMain from './AppFooterMain.vue';
import AppFooterDown from './AppFooterDown.vue';

export default{
    name:'Appfooter',
    components:{
        AppFooterTop,
        AppFooterMain,
        AppFooterDown,
    }
}
</script>
<template>
    <AppFooterTop></AppFooterTop>
    <AppFooterMain></AppFooterMain>
    <AppFooterDown></AppFooterDown>
</template>
<style lang="scss" scoped></style>