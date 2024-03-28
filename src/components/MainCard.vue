<template>
    <div class="wrapper">
        <div class="main-container">
            <div class="container-one">
                <div class="profile">
                    <img src="../assets/profilepic.jpg" alt="">
                    <h3>John Mark Sumagang</h3>
                    <p>SOFTWARE DEVELOPER EYY</p>
                </div>
                <div class="social-link">
                    <div class="link">
                        <a href="https://github.com/RimuruIguest/TheGentlemen" target="blank">
                            <img src="../assets/github.jpg" alt="">
                            <h2>GITHUB</h2>
                        </a>
                    </div>
                    <div class="link">
                        <a href="https://www.facebook.com/jan.sumagang.9" target="blank"> 
                            <img src="../assets/facebook.jpg" alt="">
                            <h2>FACEBOOK</h2>
                        </a>
                    </div>
                    <div class="link">
                        <a href="https://www.instagram.com/windjayjo/" target="blank">
                            <img src="../assets/instagram.jpg" alt="">
                            <h2>INSTAGRAM</h2>
                        </a>
                    </div>
                    <div class="link">
                        <a href="https://twitter.com/NotASlime24" target="blank">
                            <img src="../assets/twitter.jpg" alt="">
                            <h2>TWITTER</h2>
                        </a>
                    </div>
                </div>
            </div>
            <div class="container-two">
                <div class="about me ">
                    <h1>About Me</h1>
                    <p>John Mark Sumagang, an 18-year-old resident of Bangbang, Cordova, aspires to become a millionaire.</p>
                    <div class="Language-Section">
                        <h1>Language Studied</h1>
                        <div class="logos">
                            <img src="../assets/japan.jpg" alt="">
                            <img src="../assets/english.jpg" alt="">
                            <img src="../assets/bisaya.jpg" alt="">
                            <div class="button-container">
                                <div class="project-button">
                                    <a href="">Contact Number : 0909090909</a>
                                </div>
                                <div class="project-button">
                                    <a href="">EMAIL: rimuruiguest24@gmail.com</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>


<style scoped >
.wrapper{
    display: flex;
    justify-content: center;
}
img{
    height:40px;
}
.main-container{
    display: flex;
    flex-direction: row;
    background-color: aquamarine;
    border-radius: 3px;
    width: 60%;
    background-color: rgb(33, 209, 118);
    box-shadow: rgb(0, 0,0) 0px 3px 8px;
   
}
.container-one{
    background-color: rgb(206, 239, 178);
    width: 30%;
    padding: 3.5%;
    border-radius: 3px;
    
    box-shadow: rgb(0, 0,0) 0px 3px 8px;
}
.profile img{
    height: 6rem;
    border-radius: 10%;
    box-shadow: rgb(0, 0,0) 0px 3px 8px;
}
.link a{
    text-decoration: none;
    color: #2c3e50;
    font-size: 10px;
    box-shadow: rgb(0, 0,0) 0px 3px 8px;
}
.link img{
    height: 3rem;
}
.container-two{
   margin-top: auto;
    margin: 1.5%;
    width: 80%; 
    border-radius: 50px;
  
}
.about-me{
    text-align: middle;
    box-shadow: rgb(0, 0, 0) 0px 3px 8px;
}
.logos img{
    height: 5rem;
    border-radius: 50%;
   
}
.button-container{
    margin-top: 3%;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
}
.project-button{
    background-color: #3fe19b;
    border-radius: 15px;
    padding: 5px;
    margin: 5px;
    box-shadow: rgba(0, 0, 0,) 0px 3px 8px; 
}
.project-button a{
    text-decoration: none;
    color: #000407;;
}
@media only screen and (max-width:540px) {
    .main-container{
        width: 54%;
    }
}
</style>
