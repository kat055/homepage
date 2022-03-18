<script setup>

</script>

<template>
<div class="background">
<div class="header">
    <div class="logo" style="background: white;" >JUO</div>

    <button class="search" type="text">SEARCH</button>

<div class="top">
    <img class="img1" src="https://img.freepik.com/free-photo/interior-design-decoration-mock-up-furniture-cozy-living-room-empty-concrete-wall-texture-background-3d-rendering_221619-875.jpg">
    <div class="list" style="position:absolute; top:20px">PROJECTS</div>
    <div class="list" style="position:absolute; top:40px">OBJECTS</div>
    <div class="list" style="position:absolute; top:60px">ABOUT</div>
    <div class="list" style="position:absolute; top:80px">CONTACT</div>

    <div class="title">Furniture & <br> interior design
    <div style="font-size:large; word-spacing: 10px">Founded in 2017 by John Doe, the <br>
    studio is accustomed to creating <br>
    remarkable environments.</div>
    </div>
</div>
</div>
<div class="bottom">
    <div style="color: white; font-family: roboto; font-size: x-large; font-weight: bold; padding-top: 1in; padding-left: 0.5in;">
        2017 <div style="font-size: medium; font-weight:lighter;">Since</div></div>
    <img class="img2" src="https://momeld.files.wordpress.com/2008/01/bild222.jpg">
    <img class="img3" src="https://cdn.shopify.com/s/files/1/0045/5104/9304/t/27/assets/AC_ECOM_SITE_2020_REFRESH_1_INDEX_M2_THUMBS-V2-1.jpg?v=8913815134086573859">

<div class="objects">
    <div style="font-size: 1in;">Objects</div>
    <div style="font-size: 50;">We are motivated by pushing the <br>
    possibilities of form and exploring different <br>
    techniques to challenge what exists.</div>
    <form>
        <button class="explore" type="submit">EXPLORE</button>
    </form>
</div>
</div>
</div>
</template>

<style>
.background{
    height: whole-page;
    width: whole-page;
    margin: none;
    background: linear-gradient(to right, rgba(156, 157, 174, 0.78), rgba(193, 119, 109, 0.78), rgba(145, 43, 51, 1),rgba(53, 25, 28, 1))
}
.logo{
    height: 40px;
    width: 70px;
    background-color: white;
    display: flex;
    justify-content: center;
    padding-top: 10px;
    margin: 40px;
    font-family: roboto;
    font-weight: bold;
    font-size: 25px;

}
.search{
    font-family: roboto;
    height: 0.25in;
    width: 4in;
    border-top: none;
    border-left: none;
    border-right: none;
    border-bottom-color: white;
    position: absolute;
    top: 0.77in;
    left: 1.5in;
    text-align: left;
    background-color: transparent;
    color: white;
}
.header{
    display: flex;
    flex-direction: row;
}
.img1{
    margin: none;
    padding-left: 5.25in;
    height: 5in;
    width: 6.5in;
}
.list{
    color: white;
    padding-left: 10.5in;
}
.title{
    color: white;
    font-family: roboto;
    font-size: 1in;
    position: absolute;
    top: 2in;
    left: 2in;
}
.img2{
    height: 3in;
    padding-top: 1in;
    padding-left: 0.5in;
}
.img3{
    height: 2in;
    position: absolute;
    left: 4.5in;
    padding-top: 2in;
}
.objects{
    color: white;
    padding-left: 1.25in;
    padding-top: 0.75in;
}
.bottom{
    display: flex;
    flex-direction: row;
}
.explore{
    position: absolute;
    top: 8in;
    width: 1in;
    height: 0.25in;
    font-weight: bold;
    background-color: white;
    border: none;
}
</style>
