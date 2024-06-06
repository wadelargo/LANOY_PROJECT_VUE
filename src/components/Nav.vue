<template>

<div class="container">
    <div class="left-nav">
        <img src="../wolf.png" alt="">
    </div>

    <div class="logo">
        <a href="">WOLF LOGO</a>
    </div>

    
    <div class="center-nav">
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Contact</a></li>
            <li><a href="#">More</a></li>
        </ul>
    </div>


    <div class="right-nav">
        <a href="#">Logout</a>
    </div>
</div>

</template>

<style scoped>
img{
    height: 8vh;
    width: auto;
    margin-left: 30px;
}

.container{
    display: flex;
    align-items: center;
    justify-content: space-between;
    background: rgba(20, 19, 19, 0.914);
    height: 60px;
}
.center-nav ul{
    display: flex;
    list-style: none;
    margin-left: 900px;
    
}

.center-nav li {
    padding: 15px;
    font-size: 1em;
    justify-content: center;
    align-items: center;
    text-align: center;
}

a {
    text-decoration: none;
    color: rgb(246, 245, 252);   

}
li:hover{
    background-color: rgb(54, 45, 214);
 
}
.right-nav {
    margin-right: 50px;
    font-size: 1em;
    width: 80px;
    height: 25px;
    background-color: rgb(38, 28, 129);
    text-align: center;
    border-radius: 15px;
}
.center-nav{
    display: flex;
}


</style>