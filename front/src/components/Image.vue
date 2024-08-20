<template>
    <div class="container">
      <div class="mainSec centered">
        <img src="../assets/Aziz/Aziz.png" alt="Aziz's image" class="profile-img">
        <div class="text1 textColor">
          Hi, It's <span class="text nameColor">Aziz</span>
          <SocialLinks />
        </div>
      </div>
  
      <div class="secondSec">
        <div class="inline">
          <div class="icon-text">
            <img src="../assets/icons/contact/phone.png" alt="Phone Icon" />
            <div class="text2">(+216)24335292</div>
          </div>
        </div>
  
        <div class="separator"></div>
  
        <div class="inline">
          <div class="icon-text">
            <img src="../assets/icons/contact/email.png" alt="Email Icon" />
            <div class="text2">laafine.med.aziz@gmail.com</div>
          </div>
        </div>
  
        <div class="separator"></div>
  
        <div class="inline">
          <div class="icon-text">
            <img src="../assets/icons/contact/location.png" alt="Location Icon" />
            <div class="text2">Oued Ellil, Manouba, Tunisia</div>
          </div>
        </div>
      </div>
  
      <div class="textColor bottomSec">
        Motivated, passionate, and highly disciplined computer science student.
        Here you can find my CV for detailed information about my skills.
        <a href="https://laafinebio.netlify.app/assets/CV-CNK93nxL.pdf">
          <img class="flag-icon" src="../assets/icons/flags/france.png" alt="LinkedIn" />
        </a>
        <a href="https://laafinebio.netlify.app/assets/Resume-DgidOVQH.pdf">
          <img class="flag-icon" src="../assets/icons/flags/unitedKingdom.png" alt="LinkedIn" />
        </a>
      </div>
  
      <div class="footer">© 2024 Scylla development. All rights reserved.</div>
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
  padding: 0 20px;
}

.centered {
  justify-content: center;
  align-items: center;
}

.mainSec {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
}

.profile-img {
  width: 300px;
  height: 300px;
  margin-bottom: 20px;
}

.secondSec {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 20px 0;
  color: #fff;
  margin-bottom: 3rem;
}

.inline {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-bottom: 20px;
}

.bottomSec {
  text-align: center;
  padding: 20px;
  color: #fff;
}

.text1 {
  font-size: 2rem;
  font-family: "Montserrat", sans-serif;
  margin-bottom: 10px;
}

.text2 {
  font-size: 1.2rem;
  font-family: "Montserrat", sans-serif;
}

.nameColor {
  color: #FED453;
  font-weight: bold;
}

.textColor {
  color: white;
}

.icon-text {
  text-align: center;
}

.icon-text img {
  width: 24px;
  height: 24px;
  margin-bottom: 10px;
}

.separator {
  width: 60%;
  height: 1px;
  background-color: #555;
  margin: 20px auto;
}

.flag-icon {
  vertical-align: middle;
  margin: 10px;
}

.footer {
  text-align: center;
  padding: 10px 0;
  background-color: #333;
  color: #fff;
  margin-top: auto;
}

@media (min-width: 768px) {
  .mainSec {
    flex-direction: row;
  }

  .text1 {
    font-size: 3rem;
  }

  .secondSec {
    flex-direction: row;
    justify-content: space-around;
  }

  .separator {
    width: 1px;
    height: 50px;
    margin: 0 15px;
  }

  .bottomSec {
    margin-bottom: 5rem;
  }
}

@media (min-width: 1024px) {
  .text1 {
    font-size: 4rem;
  }

  .text2 {
    font-size: 1.5rem;
  }

  .profile-img {
    width: 400px;
    height: 400px;
  }

  .secondSec {
    margin-bottom: 5rem;
  }
}
</style>