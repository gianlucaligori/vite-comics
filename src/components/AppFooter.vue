<script>
</script>

<template>
     <footer>
        <div class="logos_links" >
            <a href="">Digital comics</a>
            <a href="">DC Merchandise</a>
            <a href="">Subscription</a>
            <a href="">Comic Shop Locator</a>
            <a href="">DC POWER VISA</a>
        </div>


       <div class="footer_links">
        <div class="ul_pack">
                <ul>
                    <h4>DC COMICS</h4>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>

                <ul>
                    <h4>DC</h4>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>
                
                <ul>
                    <h4>SHOP</h4>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibles</li>
                </ul>


                <ul>
                    <h4>SITES</h4>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>
            </div>
                
                <div>
                    <img class="logo_dc_bg" src="../assets/img/dc-logo-bg.png" alt="">
                </div>
        </div>

        <div class="footer_signup">
                <span class="signup_btn" >
                    SIGN UP NOW
                </span>

                <div class="socials_btn" >
                    <span class="flw_btn"> FOLLOW US </span>
                    <i class="fa-brands fa-facebook"></i>
                    <i class="fa-brands fa-facebook"></i>
                    <i class="fa-brands fa-facebook"></i>
                    <i class="fa-brands fa-facebook"></i>
                    <i class="fa-brands fa-facebook"></i>
                </div>


       </div>


     </footer>
</template>

<style lang="scss" scoped>

@use "../assets/styles/partials/variables" as *;


footer {
    @include footer
}

.logos_links {
    @include logos_links
}

a {
    @include a_container
}

.footer_links {
    background-image: url(../assets/img/footer-bg.jpg);
    height: 300px;
    display: flex;
    align-items: center;
    justify-content: space-around;
}

h4 {
    margin-bottom: .5rem;
}

ul {
    color: white;
    list-style:none;
}

.ul_pack {
    display: flex;
    gap: 3rem;
}

li {
    padding: .15rem;
    font-size: .8rem;
}

.logo_dc_bg {
    height: 400px;
    z-index: -1;
    align-items: center;

}

.footer_signup {
    height: 100px;
    background-color: #303030;
    display: flex;
    justify-content: space-around;
    align-items: center;
    position: relative;
    z-index: 0;
}

.signup_btn {
    border: 2px solid rgba(2,130,249,255);
    padding: .5rem;
    color:white
}

.flw_btn {
    margin-inline: 1rem;
    color: rgba(2,130,249,255);
    font-weight: 800;
}



i {
    margin-inline: .2rem;
    color: #797979;
}


</style>