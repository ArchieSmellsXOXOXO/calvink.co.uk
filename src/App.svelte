<main>
    <style>
body{
    background-color: black;
}
</style>
</main>



<main>
    <b>
     <div>
        <nav>
            <a href="https://www.calvink.co.uk">Home</a>
            <a href="#">about</a>
            <a href="#">blog</a>
            <a href="#">portfolio</a>
            <a href=".\contact.html">contact</a>
            <div class="animation"></div>
        </nav>
     </div>
    </b>
</main>



<div class="logo">
    <b><h1>||カルバン||</h1></b> 
</div>



















<style>



    .logo{
        color: white;
        margin: 30px;
        font-size: large;
    }
*{
    margin: 0;
    padding: 0;
}
    nav {
    margin-top: 27px auto 0;

    position: relative;
    width: 590px;
    height: 50px;
    background-color: black;
    border-radius: 8px;
    font-size: 0;
    float: right
}

nav a {
    line-height: 50px;
    height: 100%;
    font-size: 15px;
    display: inline-block;
    position: relative;
    z-index: 1;
    text-decoration: none;
    text-transform: uppercase;
    text-align: center;
    color: red;
    cursor: pointer;
}

nav .animation {
    position: absolute;
    height: 100%;
    top: 0;
    z-index: 0;
    transition: all .5s ease 0s;
    border-radius: 8px;
}

a:nth-child(1){
    width: 100px;
}

a:nth-child(2){
    width: 110px;
}

a:nth-child(3){
    width: 100px;
}

a:nth-child(4){
    width: 160px;
}

a:nth-child(5){
    width: 120px;
}

nav .start-Home, a:nth-child(1):hover~.animation {
    width: 110px;
    left: 0px;
    background-color: white;
}

nav .start-About, a:nth-child(2):hover~.animation {
    width: 110px;
    left: 100px;
    background-color: white;
}

nav .start-Blog, a:nth-child(3):hover~.animation {
    width: 100px;
    left: 210px;
    background-color: white;
}

nav .start-Portfolio, a:nth-child(4):hover~.animation {
    width: 160px;
    left: 310px;
    background-color: white;   
}

nav .start-Contact, a:nth-child(5):hover~.animation {
    width: 120px;
    left: 480px;
    background-color: white;   
}




</style>
