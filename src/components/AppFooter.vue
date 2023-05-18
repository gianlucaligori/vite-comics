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
                <h4>SHOP</h4>
                <li>Shop DC</li>
                <li>Shop DC Collectibles</li>

            </ul>
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
}

h3 {
    margin-bottom: .5rem;
}

ul {
    color: white;
    list-style:none;
    padding: 1rem;
}

li {
    padding: .15rem;
    font-size: .8rem;
}

</style>