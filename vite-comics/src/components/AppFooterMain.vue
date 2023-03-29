<script>

export default{
    name: 'AppFooterMain'
}
</script>
<template>
    <div class="container">
        <div class="comics-shop">
            <div class="comics">
                <ul>
                    <li><h3>DC COMICS</h3></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">News</a></li>
                </ul>
            </div>
            <div class="shop">
                <ul>
                    <li><h3>SHOP</h3></li>
                    <li><a href="#">Shop DC</a></li>
                    <li><a href="#">Shop DC Collectibles</a></li>
                </ul>
            </div>
        </div>
        <div class="dc">
            <ul>
                <li><h3>DC</h3></li>
                <li><a href="#">Terms Of Use</a></li>
                <li><a href="#">Privacy policy(New)</a></li>
                <li><a href="#">Ad Choices</a></li>
                <li><a href="#">Advertising</a></li>
                <li><a href="#">Jobs</a></li>
                <li><a href="#">Subsciptions</a></li>
                <li><a href="#">Talent Workshops</a></li>
                <li><a href="#">CPSC Certificates</a></li>
                <li><a href="#">Ratings</a></li>
                <li><a href="#">Shop Help</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>
        </div>
        <div class="sites">
            <ul>
                <li><h3>SITES</h3></li>
                <li><a href="#">DC</a></li>
                <li><a href="#">MAD Magazine</a></li>
                <li><a href="#">DC Kids</a></li>
                <li><a href="#">DC Universe</a></li>
                <li><a href="#">DC Power Visa</a></li>
            </ul>
        </div>
        <div class="logo-backgroud">
            <img src="../../public/dc-logo-bg.png" alt="">
        </div>
    </div>
</template>
<style lang="scss" scoped>
.container{
    display: flex;
    background-image: url(../../public/footer-bg.jpg);
}
.logo-backgroud{
    margin-left: auto;
}
.logo-backgroud img{
    width: 400px;
    height: 400px;
    object-fit: cover;
}

a{
    color: gray;
}
h3{
    color: white;
}
</style>