<template>

  <div class="container">
      <div class="profile-box">

          <div class="profile-content-box">

              <div class="profile-content-img">
                  <img class="profile-img" src="~/assets/8.jpg"/>
              </div>

              <div class="profile-content">
                  <div class="profile-name">
                      <div>
                          Hi, I'm 
                          <div class="profile-blod-name">
                            Charnchon Subsiri
                          </div> 
                      </div>
                      <div>
                          SOFTWARE DEVELOPER
                      </div>
                  </div>

                  <div class="line"></div>

                  <div class="profile-about-block">
                      <div class="profile-about">
                          <div>
                              AGE
                          </div>
                          <div>
                              GENDER
                          </div>
                          <div>
                              ADRESS
                          </div>
                          <div>
                              E-MAIL
                          </div>
                          <div>
                              PHONE
                          </div>
                      </div>
                      <div class="profile-about">
                           <div>
                               19
                           </div>
                           <div>
                               male
                           </div>
                           <div>
                               10/4 84140 Thailand
                           </div>
                           <div>
                               boatcharnchon@gmail.com
                           </div>
                           <div>
                               0833633344
                           </div>
                      </div>
                  </div>

                    <div class="line"></div>

                  <div class="profile-credit-block">
                      <div class="profile-credit-lebel">
                          ACADEMY
                      </div>
                      <div class="profile-credit-img-block">
                            <img class="profile-credit-img" src="~/assets/9.png"/>
                            <img class="profile-credit-img" src="~/assets/10.png"/>
                            <img class="profile-credit-img" src="~/assets/11.png"/>
                      </div>
                  </div>



              </div>
               
          </div>

          <div class="profile-social-block">
              <a href=" https://web.facebook.com/boat.charnchon/ ">
                <i class="fab fa-facebook"></i>
              </a>
              <a href="https://www.instagram.com/boat_charnchon/">
                <i class="fab fa-instagram"></i>
              </a>
              <a href="">
                <i class="fab fa-youtube"></i>
              </a>
              <a href="">
                  <i class="fab fa-twitter"></i>
              </a>
          </div>

      </div>
       
  </div>
</template>

<script>

</script>

<style>
    .container {
        height: 800px;
        width: 100%;
        background:   linear-gradient(
          rgba(0, 0, 0, 0.5), 
          rgba(0, 0, 0, 0.5)
        ), url("~assets/3.jpg");
        background-repeat: no-repeat;
        background-position: top,center;
        opacity: 1.5;
        display: flex;
        justify-content: center;
        align-items: center;
        font-family: 'Advent Pro', sans-serif;
    }

    .profile-box {
        width: 100%;
        max-width: 980px;
        background-color: #ffffff;
        height: auto;
        box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
    }

    .profile-content-box {
        height: auto;
        padding: 5% 5%;
        display: flex;
        justify-content: flex-start;

    }

    .profile-content {
        width: 60%;
    }

    .profile-name {
        font-size: 30px;
    }

    .profile-name :first-child {
        display: flex;
    }

    .profile-name :nth-child(2) {
        padding-top: 5px;
        font-weight: 100;
        font-family: 'Advent Pro', sans-serif;
    }

    .profile-blod-name {
        padding: 0 0 0 10px;
        font-weight: bold;
        font-family: 'Anton', sans-serif;
        color: #ff9900;
    }

    .line {
        width: 100%;
        height: 1px;
        background-color: #222;
        margin: 10px 0;
    }

    .profile-about-block {
        margin: 15px 0 0 0;
        display: flex;
        font-size: 20px;

    }

    .profile-about {
        padding: 0 20px 0 0 ;
    }

    .profile-about-block:first-child {
        width: 30%;
    }

    .profile-about-block:nth-child(2) {
        width: 70%;
    }

    .profile-credit-lebel {
        display: flex;
        justify-content: center;
        font-size: 30px;
        margin: 40px 0;
    }

    .profile-credit-img-block {
        display: flex;
        justify-content: center;
    }

    .profile-credit-img {
        height: 75px;
        margin: 0 20px;
    }

    .profile-img {
        width: 300px;
        height: auto;
        margin: 0 30px 0 0;
    }

    .profile-social-block {
        background-color:#3b8070;
        height: 75px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .fab {
        color: #ffffff;
        font-size: 40px;
        margin: 0 15px;

    }
   

</style>