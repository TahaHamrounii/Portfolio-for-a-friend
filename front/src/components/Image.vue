<template>
<div class="container">

    <div class="mainSec centered">
        <img src="../assets/Aziz/Aziz.png" alt="Aziz's image">
        <div class="text1 textColor">Hi, It's <span class="text nameColor">Aziz</span> 
        <SocialLinks/>
        </div>
    </div>

    <div class="secondSec">
        <div class="inline">
            <div class="icon-text">
                <img src="../assets/icons/contact/phone.png" alt="Phone Icon">
                <div class="text2">(+216)24335292</div>
            </div>
        </div>

        <div class="separator"></div>

        <div class="inline">
            <div class="icon-text">
                <img src="../assets/icons/contact/email.png" alt="Email Icon">
                <div class="text2">laafine.med.aziz@gmail.com</div>
            </div>
        </div>

        <div class="separator"></div>

        <div class="inline">
            <div class="icon-text">
                <img src="../assets/icons/contact/location.png" alt="Location Icon">
                <div class="text2">Oued Ellil, Manouba, Tunisia</div>
            </div>
        </div>
    </div>

    <div class="textColor bottomSec">
        Motivated, passionate and highly disciplined computer science student, here you can find my CV for detailed information about my skills

        <a href="https://laafinebio.netlify.app/assets/CV-CNK93nxL.pdf">
            <img class="flag-icon" src="../assets/icons/flags/france.png" alt="LinkedIn" />
        </a>
        
        <a href="https://laafinebio.netlify.app/assets/Resume-DgidOVQH.pdf">
            <img class="flag-icon" src="../assets/icons/flags/unitedKingdom.png" alt="LinkedIn" />
        </a>    
    </div>

    <div class="footer">
        © 2024 Scylla development. All rights reserved.
    </div>
</div>

</template>

<script setup>
import SocialLinks from '../components/SocialLinks.vue'
</script>

<style scoped>
.container {
    display: flex;
    flex-direction: column;
    min-height: 100%;
}
.centered {
    justify-content: center;
    align-items: center;
}
.inline {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.mainSec {
    display: flex;
    margin-top: 10rem;
    height: 20rem;
}
.secondSec{
    display: flex;
    justify-content: space-around;
    padding: 10px 0;
    color: #fff;
    margin-bottom: 5rem;
}

.bottomSec{
    justify-content: center;
    padding: 10px 0;
    color: #fff;
    margin-bottom: 5rem;
}

.text1 {
    font-size: 50px;
    font-family: "Montserrat", sans-serif;
    font-weight: bold;
}
.text2 {
    font-size: 20px;
    font-family: "Montserrat", sans-serif;
}
.text3{
    font-size: 18px;
    font-family: "Montserrat", sans-serif;
    font-weight: bold;
}

.nameColor {
    color: #FED453;
}
.textColor {
    color: white;
}

.icon-text {
    text-align: center;
}

.icon-text img {
    display: block;
    margin: 0 auto;
    width: 24px;
    height: 24px;
}
.icon-text div {
    margin-top: 5px;
}
.separator {
    width: 1px;
    height: 50px;
    background-color: #555;
    margin: 0 15px;
}

.flag-icon {
    vertical-align: middle;
}

.footer {
    text-align: center;
    padding: 10px 0;
    background-color: #333;
    color: #fff;
    margin-top: auto;
}

</style>