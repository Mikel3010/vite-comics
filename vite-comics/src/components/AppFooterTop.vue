<script>
export default{
    name: 'AppFooterTop'
}
</script>
<template>
    <div class="container">
        <ul>
            <li>
                <div>
                    <img src="../../public/buy-comics-digital-comics.png" alt="">
                </div>
                <div>
                    <a href="">DIGITAL COMICS</a>
                </div>
            </li>
            <li>
                <div>
                    <img src="../../public/buy-comics-merchandise.png" alt="">
                </div>
                <div>
                    <a href="">DC MERCHANDISE</a>
                </div>
            </li>
            <li>
                <div>
                    <img src="../../public/buy-comics-subscriptions.png" alt="">
                </div>
                <div>
                    <a href="">SUBSCRIPTIONS</a>
                </div>
            </li>
            <li>
                <div>
                    <img src="../../public/buy-comics-shop-locator.png" alt="">
                </div>
                <div>
                    <a href="">COMIC SHOP LOCATOR</a> 
                </div>
            </li>
            <li>
                <div>
                    <img src="../../public/buy-comics-shop-locator.png" alt="">
                </div>
                <div>
                    <a href="">DC POWER VISA</a>
                </div>
            </li>
        </ul>
    </div>
</template>
<style lang="scss" scoped>
.container{
    background-color: #0282f9;
    margin: 0;
    padding: 20PX 0;
}

a{
    color: white;
}
ul{
    display: flex;
    margin: 0;
}
img{
    height: 55px;
}
</style>