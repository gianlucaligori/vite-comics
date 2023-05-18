<script>

</script>

<template>
    <div class="bar">
        <img class="size" src="../assets/img/dc-logo.png" alt="">
        <ul class="text">
            <li>CHARACTERS</li>
            <li>COMICS</li>
            <li>MOVIES</li>
            <li>TV</li>
            <li>GAMES</li>
            <li>COLLECTIBLES</li>
            <li>VIDEOS</li>
            <li>FANS</li>
            <li>FANS</li>
            <li>NEWS</li>
            <li>SHOP</li>
        </ul>
    </div>
 
</template>

<style lang="scss" scoped >
@use './../assets/styles/partials/variables' as *;
.bar{
    @include nav-bar;
}

.text{
    @include color-text;
}

.size{
    @include size-img;
}
</style>
