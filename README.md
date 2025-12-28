# Ex09 Event Registration Web Application
# Date:27/12/25
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
```
FOR LAYOUT 1:
index.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro">
      <img class="rectangle" src="img/rectangle-1.png" />
      <img class="img" src="img/rectangle-2.png" />
      <p class="SPORTS-DAY-EVENTS">
        <span class="text-wrapper"
          >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <br /><br /><br
        /></span>
        <span class="span">&nbsp;&nbsp; SPORTS DAY  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; EVENTS <br /></span>
        <span class="text-wrapper"></span>
      </p>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-2">LOGIN</div>
      <div class="text-wrapper-3">REGISTER</div>
    </div>
  </body>
</html>


globals.css
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css
.iphone-pro {
  background-color: #0d7b6e;
  width: 100%;
  min-width: 402px;
  min-height: 874px;
  position: relative;
}

.iphone-pro .rectangle {
  position: absolute;
  top: 117px;
  left: 81px;
  width: 239px;
  height: 210px;
  object-fit: cover;
}

.iphone-pro .img {
  position: absolute;
  top: 0;
  left: 0;
  width: 402px;
  height: 99px;
  object-fit: cover;
}

.iphone-pro .SPORTS-DAY-EVENTS {
  position: absolute;
  top: 291px;
  left: 37px;
  width: 328px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #c72b2b;
  font-size: 12px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .text-wrapper {
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #c72b2b;
  font-size: 12px;
  letter-spacing: 0;
}

.iphone-pro .span {
  font-size: 40px;
}

.iphone-pro .div {
  position: absolute;
  top: 540px;
  left: 105px;
  width: 165px;
  height: 38px;
  background-color: #d9d9d9;
}

.iphone-pro .rectangle-2 {
  position: absolute;
  top: 540px;
  left: 105px;
  width: 165px;
  height: 38px;
  background-color: #f53e3e;
}

.iphone-pro .rectangle-3 {
  position: absolute;
  top: 617px;
  left: 105px;
  width: 165px;
  height: 41px;
  background-color: #4cd33d;
}

.iphone-pro .text-wrapper-2 {
  position: absolute;
  top: 547px;
  left: 157px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro .text-wrapper-3 {
  position: absolute;
  top: 626px;
  left: 147px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}


styleguide.css

:root {
  --d-9d-9d-9: rgba(249, 110, 110, 1);
}


LAYOUT 2:
index.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro">
      <div class="rectangle"></div>
      <div class="text-wrapper">SPORTS DAY EVENTS</div>
      <img class="star" src="img/star-1.svg" />
      <img class="img" src="img/star-2.svg" />
      <img class="star-2" src="img/star-3.svg" />
      <img class="star-3" src="img/star-4.svg" />
      <img class="star-4" src="img/star-5.svg" />
      <div class="CRICKET-BATMINTON">
        CRICKET<br /><br />BATMINTON<br /><br />VOLLEY BALL<br /><br />BASEBALL<br /><br />HOCKEY<br /><br />TABLE
        TENNIS<br /><br />RELAY<br /><br />FOOT BALL<br /><br />KHO-KHO
      </div>
      <img class="star-5" src="img/star-6.svg" />
      <img class="star-6" src="img/star-7.svg" />
      <img class="star-7" src="img/star-8.svg" />
      <img class="star-8" src="img/star-9.svg" />
    </div>
  </body>
</html>


globals.css
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css
.iphone-pro {
  background-color: #eb763c;
  width: 100%;
  min-width: 402px;
  min-height: 874px;
  position: relative;
}

.iphone-pro .rectangle {
  position: absolute;
  top: 80px;
  left: 12px;
  width: 379px;
  height: 64px;
  background-color: #91588c;
}

.iphone-pro .text-wrapper {
  position: absolute;
  top: 97px;
  left: 77px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #00ff8c;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .star {
  top: 191px;
  position: absolute;
  left: 64px;
  width: 26px;
  height: 26px;
}

.iphone-pro .img {
  top: 254px;
  position: absolute;
  left: 64px;
  width: 26px;
  height: 26px;
}

.iphone-pro .star-2 {
  top: 308px;
  position: absolute;
  left: 64px;
  width: 26px;
  height: 26px;
}

.iphone-pro .star-3 {
  top: 368px;
  position: absolute;
  left: 64px;
  width: 26px;
  height: 26px;
}

.iphone-pro .star-4 {
  top: 429px;
  position: absolute;
  left: 64px;
  width: 26px;
  height: 26px;
}

.iphone-pro .CRICKET-BATMINTON {
  position: absolute;
  top: 195px;
  left: 126px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #221111;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .star-5 {
  top: 483px;
  position: absolute;
  left: 64px;
  width: 26px;
  height: 26px;
}

.iphone-pro .star-6 {
  top: 543px;
  position: absolute;
  left: 64px;
  width: 26px;
  height: 26px;
}

.iphone-pro .star-7 {
  top: 604px;
  position: absolute;
  left: 64px;
  width: 26px;
  height: 26px;
}

.iphone-pro .star-8 {
  top: 658px;
  position: absolute;
  left: 64px;
  width: 26px;
  height: 26px;
}

styleguide.css

:root {
  --d-9d-9d-9: rgba(249, 110, 110, 1);
}


LAYOUT 3:
index.html:
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro">
      <div class="rectangle"></div>
      <div class="text-wrapper">EVENT REGISTRATION FORM</div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <img class="img" src="img/rectangle-13.svg" />
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <div class="rectangle-7"></div>
      <div class="text-wrapper-2">FULL NAME</div>
      <div class="text-wrapper-3">GENDER</div>
      <div class="text-wrapper-4">AGE</div>
      <div class="text-wrapper-5">REGISTER NO</div>
      <div class="text-wrapper-6">DEPARTMENT</div>
      <div class="text-wrapper-7">MOBILE NUMBER</div>
      <div class="text-wrapper-8">EMAIL ID</div>
      <div class="text-wrapper-9">EVENTS REGISTERED</div>
      <div class="rectangle-8"></div>
      <div class="text-wrapper-10">SUBMIT</div>
    </div>
  </body>
</html>

globals.css:
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css:

.iphone-pro {
  background-color: #205469;
  width: 100%;
  min-width: 402px;
  min-height: 874px;
  position: relative;
}

.iphone-pro .rectangle {
  position: absolute;
  top: 75px;
  left: 13px;
  width: 376px;
  height: 55px;
  background-color: #3c1ded;
}

.iphone-pro .text-wrapper {
  position: absolute;
  top: 88px;
  left: 41px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .div {
  position: absolute;
  top: 179px;
  left: 34px;
  width: 130px;
  height: 23px;
  background-color: #d9d9d9;
}

.iphone-pro .rectangle-2 {
  position: absolute;
  top: 234px;
  left: 34px;
  width: 130px;
  height: 23px;
  background-color: #d9d9d9;
}

.iphone-pro .rectangle-3 {
  position: absolute;
  top: 289px;
  left: 34px;
  width: 130px;
  height: 23px;
  background-color: #d9d9d9;
}

.iphone-pro .rectangle-4 {
  position: absolute;
  top: 344px;
  left: 34px;
  width: 130px;
  height: 23px;
  background-color: #d9d9d9;
}

.iphone-pro .img {
  position: absolute;
  top: 399px;
  left: 34px;
  width: 130px;
  height: 23px;
}

.iphone-pro .rectangle-5 {
  position: absolute;
  top: 454px;
  left: 34px;
  width: 130px;
  height: 23px;
  background-color: #d9d9d9;
}

.iphone-pro .rectangle-6 {
  position: absolute;
  top: 509px;
  left: 34px;
  width: 130px;
  height: 23px;
  background-color: #d9d9d9;
}

.iphone-pro .rectangle-7 {
  position: absolute;
  top: 566px;
  left: 34px;
  width: 162px;
  height: 21px;
  background-color: #d9d9d9;
}

.iphone-pro .text-wrapper-2 {
  position: absolute;
  top: 182px;
  left: 53px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro .text-wrapper-3 {
  position: absolute;
  top: 239px;
  left: 65px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro .text-wrapper-4 {
  position: absolute;
  top: 294px;
  left: 81px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro .text-wrapper-5 {
  position: absolute;
  top: 349px;
  left: 49px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro .text-wrapper-6 {
  position: absolute;
  top: 404px;
  left: 49px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro .text-wrapper-7 {
  position: absolute;
  top: 457px;
  left: 40px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro .text-wrapper-8 {
  position: absolute;
  top: 512px;
  left: 62px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro .text-wrapper-9 {
  position: absolute;
  top: 569px;
  left: 38px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro .rectangle-8 {
  position: absolute;
  top: 636px;
  left: 150px;
  width: 100px;
  height: 32px;
  background-color: #43843e;
}

.iphone-pro .text-wrapper-10 {
  position: absolute;
  top: 643px;
  left: 171px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

styleguide.css:
:root {
  --d-9d-9d-9: rgba(249, 110, 110, 1);
}
```

# OUTPUT:
<img width="1902" height="953" alt="image" src="https://github.com/user-attachments/assets/49eee18d-3bf3-4f0d-81ca-568c01524e09" />

# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
