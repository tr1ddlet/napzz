<template>
  <div id="first">
    <div id="header">
      <div id="left">
        <h1 id="title">napzz</h1>
        <div id="slogan">
          <p class="sloganText">Wake up</p>
          <p class="sloganText">at your best.</p>
        </div>
        <div id="comingSoon">
          <p>Coming Soon</p>
        </div>
      </div>

      <div id="middle">
        <button class="touchMenu">Home</button>
        <button class="touchMenu">About</button>
        <button class="touchMenu">Blog</button>
        <button class="touchMenu">Contact</button>
      </div>
    </div>

    <div id="mainBody">
      <div id="workCircles">
        <h2>How it works</h2>
        <div class="circles">
          <div class="worksInfo">
            <div class="circle circle1">
              <img src="../public/watches.png" alt="watches" class="circleIMG" />
            </div>
            <p class="analyzeInfoDescrtiption">Collect your data</p>
          </div>

          <div class="worksInfo">
            <div class="circle circle2">
              <img src="../public/brain.png" alt="brain" class="circleIMG" />
            </div>
            <p class="analyzeInfoDescrtiption">Analyze your sleep</p>
          </div>

          <div class="worksInfo">
            <div class="circle circle3">
              <img src="../public/clock.png" alt="clock" class="circleIMG" />
            </div>
            <p class="analyzeInfoDescrtiption">Wake you at the optimal time</p>
          </div>
        </div>
        <p class="shortDescr">All you need is an Apple watch and 5 nights of sleep</p>
      </div>

      <div class="postContact">
        <p class="contactDescr">Be the first to try napzz</p>
        <input type="email" class="input-box" autocomplete="email" placeholder="Email address"/>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style>
#middle{
    display: flex;
    align-items: start; 
    gap: 60px;
    margin-left: 40px;
    margin-top: 15px;

}
.touchMenu{
    font-family: "Manrope", sans-serif;
    font-weight: lighter;
    font-size: 20px;
    border: none;
    cursor: pointer;
    background-color: #f2f9ff;
    color: #234c7d;

}
.input-box {
  width: 300px;
  height: 50px;
  border: none;
  outline: 0;
  border-radius: 50px;
  background-color: #f2f9ff;
  font-family: "Manrope", sans-serif;
  font-weight: lighter;
  font-size: 20px;
  color: #9EB4D4;
  padding: 0px 20px;
}
.postContact {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin: 35px;
}
.contactDescr {
  font-family: "Manrope", sans-serif;
  font-weight: bold;
  font-size: 25px;
  color: #234c7d;
}
.shortDescr {
  margin: 20px;
  font-family: "Manrope", sans-serif;
  font-weight: lighter;
  font-size: 20px;
  color: #234c7d;
  text-align: center;
}
.analyzeInfoDescrtiption {
  color: #234c7d;
  font-size: 16px;
  font-family: "Manrope", sans-serif;
  font-weight: bold;
}
.circleIMG {
  /* padding-left: 5px; */
  width: 63px;
  height: 63px;
}
.circles {
  margin-top: 20px;
  display: flex;
  justify-content: center;
  gap: 200px;
}
.worksInfo {
  flex-direction: column;
  display: flex;
  text-align: -webkit-center;
}
.circle {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100px;
  height: 100px;
  border-radius: 50%;
  background-color: #f2f9ff;
}
@import url("https://fonts.googleapis.com/css2?family=Manrope:wght@200..800&display=swap");
#workCircles {
  margin-left: 35px;
  padding-top: 30px;
  
}
h2 {
  margin: 0;
  font-family: "Manrope", sans-serif;
  font-weight: bold;
  font-size: 25px;
  color: #234c7d;
}
#left {
  margin-left: 35px;
  margin-top: 15px;
}
#slogan {
  display: flex;
  flex-direction: column;
  margin-top: 3px;
  margin-bottom: 2px;
}
#comingSoon {
  font-size: 20px;
  font-family: "Manrope", sans-serif;
  background-color: #5e8bc3;
  border-radius: 65px;
  text-align: center;
  margin-bottom: 0;
  color: #ffffff;
  width: 150px;
  height: 30px;
}
.sloganText {
  font-family: "Manrope", sans-serif;
  margin: 0;
  font-weight: bold;
  font-size: 50px;
  color: #234c7d;
}
#title {
  font-family: "Manrope", sans-serif;
  font-weight: bold;
  font-size: 25px;
  margin: 0;
  color: #234c7d;
}
#header {
  background-color: #f2f9ff;
  height: 250px;
  margin: 50px 50px 0px 50px;
  border-radius: 20px 20px 0px 0px;
  font-family: manro;
  display: flex;
}
#mainBody {
  background-color: #ffffff;
  height: 500px;
  margin: 0px 50px 0px 50px;
  border-radius: 0px 0px 20px 20px;
}
</style>
