<script>
export default{
    name:'AppHeaderMenu'
}
</script>
<template>
    <div>
        <ul>
            <li><a href="#">CHARACTERS</a></li>
            <li class="blue"><a href="#">COMICS</a></li>
            <li><a href="#">MOVIES</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">GAMES</a></li>
            <li><a href="#">COLLECTIBLES</a></li>
            <li><a href="#">VIDEOS</a></li>
            <li><a href="#">FANS</a></li>
            <li><a href="#">NEWS</a></li>
            <li><a href="#">SHOP</a></li>
        </ul>
    </div>
</template>
<style lang="scss" scoped>
a{
    display: flex;
    color: black;
    padding: 60px 0;
}
.blue{
    border-bottom: 1px solid #0282f9;
}
.blue a{
    color: #0282f9;
}

ul{
    display: flex;
    padding: 0;
    gap: 10px;
    margin: 0;
}
div{
    display: flex;
    
}
</style>