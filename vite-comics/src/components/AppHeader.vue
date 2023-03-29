<script>

import AppLogo from './AppLogo.vue'
import AppHeaderMenu from './AppHeaderMenu.vue'
export default{
    name:'AppHeader',
    components:{
        AppHeaderMenu,
        AppLogo
    }
}
</script>
<template>
    <header>
        <div class="container">
            <AppLogo></AppLogo>
            <AppHeaderMenu></AppHeaderMenu>
        </div>
    </header>
</template>
<style lang="scss" scoped>
.container{
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1264px;
}
</style>