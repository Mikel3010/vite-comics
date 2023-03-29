<script>

export default{
    name: 'AppFooterDown'
}
</script>
<template>
    <div class="container">
        <div class="container-button">
            <button>SIGN-UP NOW!</button>
        </div>
        <div>
            <ul>
                <li><h2>FOLLOW US</h2></li>
                <li><a href=""><img src="../../public/footer-facebook.png" alt=""></a></li>
                <li><a href=""><img src="../../public/footer-twitter.png" alt=""></a></li>
                <li><a href=""><img src="../../public/footer-youtube.png" alt=""></a></li>
                <li><a href=""><img src="../../public/footer-pinterest.png" alt=""></a></li>
                <li><a href=""><img src="../../public/footer-periscope.png" alt=""></a></li>
            </ul>
        </div>
    </div>
</template>
<style lang="scss" scoped>
button{
    background-color: #303030;
    border: 1px #0282f9 solid;
    color: white;
    padding: 10px;
    margin-left: 40px;
}
.container{
    display: flex;
    justify-content: space-between;
    background-color:#303030;
}
.container-button{
    display: flex;
    align-items: center;
}
ul{
    display: flex;
    align-items: center;
}
li{
    padding-left: 10px;
}
h2{color: #0282f9;}
</style>