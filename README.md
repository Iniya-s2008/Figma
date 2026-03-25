# Ex08 Event Registration Web Application
## Date:20.03.2026

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:

```
iPhone 13 & 14 - 1
index.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <img class="LAST" src="img/LAST-1.png" />
      <div class="rectangle"></div>
      <img class="sec-logo" src="img/sec-logo-01as-2.png" />
      <div class="text-wrapper">THANK YOU</div>
      <p class="div">WE ARE ALL EAGERLY WAITING FOR YOUR PARTICIPATION IN THE SPORTS EVENT</p>
      <div class="CONTACT-US">CONTACT US<br />INIYA2008@GMAIL.COM<br />PHONE :<br />9173903887</div>
    </div>
  </body>
</html>

style.css
.iphone {
  background-color: #ffffff;
  width: 100%;
  min-width: 390px;
  min-height: 844px;
  position: relative;
}

.iphone .LAST {
  position: absolute;
  top: 0;
  left: 0;
  width: 390px;
  height: 844px;
  aspect-ratio: 0.67;
  object-fit: cover;
}

.iphone .rectangle {
  position: absolute;
  top: 160px;
  left: 28px;
  width: 333px;
  height: 71px;
  background-color: #d9d9d9;
}

.iphone .sec-logo {
  position: absolute;
  top: 162px;
  left: 20px;
  width: 341px;
  height: 69px;
  aspect-ratio: 4.97;
  object-fit: cover;
}

.iphone .text-wrapper {
  position: absolute;
  top: 279px;
  left: 67px;
  width: 319px;
  font-family: "Karma-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .div {
  position: absolute;
  top: 342px;
  right: 16px;
  width: 329px;
  font-family: "Kavoon-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .CONTACT-US {
  position: absolute;
  top: 755px;
  left: 89px;
  width: 272px;
  font-family: "Kavoon-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 13px;
  letter-spacing: 0;
  line-height: normal;
}

iPhone 16 Plus - 2
index.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-plus">
      <img class="page" src="img/page3-1.png" />
      <div class="text-wrapper">EVENT REGISTRATION FORM</div>
      <div class="div">FILL THE DETAILS</div>
      <div class="rectangle"></div>
      <div class="text-wrapper-2">FULL NAME</div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <img class="img" src="img/rectangle-9.svg" />
      <div class="text-wrapper-3">GENDER</div>
      <div class="text-wrapper-4">AGE</div>
      <div class="text-wrapper-5">REGISTER NUMBER</div>
      <div class="text-wrapper-6">DEPARTMENT</div>
      <div class="text-wrapper-7">MOBILE NUMBER</div>
      <div class="text-wrapper-8">EMAIL ID</div>
      <div class="text-wrapper-9">EVENT TO REGISTER</div>
    </div>
  </body>
</html>

style.css
.iphone-plus {
  background-color: #ffffff;
  width: 100%;
  min-width: 413px;
  min-height: 840px;
  position: relative;
}

.iphone-plus .page {
  position: absolute;
  top: 0;
  left: 0;
  width: 413px;
  height: 840px;
  aspect-ratio: 0.67;
  object-fit: cover;
}

.iphone-plus .text-wrapper {
  position: absolute;
  top: 73px;
  left: 36px;
  width: 341px;
  font-family: "Kavoon-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-plus .div {
  position: absolute;
  top: 121px;
  left: 48px;
  width: 231px;
  font-family: "Karla-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-plus .rectangle {
  top: 163px;
  height: 35px;
  background-color: #d9d9d9;
  position: absolute;
  left: 48px;
  width: 281px;
}

.iphone-plus .text-wrapper-2 {
  position: absolute;
  top: 167px;
  left: 71px;
  width: 244px;
  font-family: "Jost-MediumItalic", Helvetica;
  font-weight: 500;
  font-style: italic;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-plus .rectangle-2 {
  top: 212px;
  height: 35px;
  background-color: #d9d9d9;
  position: absolute;
  left: 48px;
  width: 281px;
}

.iphone-plus .rectangle-3 {
  top: 257px;
  height: 35px;
  background-color: #d9d9d9;
  position: absolute;
  left: 48px;
  width: 281px;
}

.iphone-plus .rectangle-4 {
  top: 318px;
  height: 35px;
  background-color: #d9d9d9;
  position: absolute;
  left: 48px;
  width: 281px;
}

.iphone-plus .rectangle-5 {
  top: 367px;
  height: 35px;
  background-color: #d9d9d9;
  position: absolute;
  left: 48px;
  width: 281px;
}

.iphone-plus .rectangle-6 {
  top: 421px;
  height: 35px;
  background-color: #d9d9d9;
  position: absolute;
  left: 48px;
  width: 281px;
}

.iphone-plus .img {
  top: 481px;
  height: 106px;
  position: absolute;
  left: 48px;
  width: 281px;
}

.iphone-plus .text-wrapper-3 {
  position: absolute;
  top: 217px;
  left: 71px;
  width: 269px;
  font-family: "Jost-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-plus .text-wrapper-4 {
  position: absolute;
  top: 265px;
  left: 71px;
  width: 243px;
  font-family: "Jost-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-plus .text-wrapper-5 {
  position: absolute;
  top: 324px;
  left: 71px;
  width: 248px;
  font-family: "Jost-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-plus .text-wrapper-6 {
  position: absolute;
  top: 375px;
  left: 71px;
  width: 252px;
  font-family: "Jost-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-plus .text-wrapper-7 {
  position: absolute;
  top: 430px;
  left: 71px;
  width: 294px;
  font-family: "Jost-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-plus .text-wrapper-8 {
  position: absolute;
  top: 486px;
  left: 79px;
  width: 256px;
  font-family: "Jost-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-plus .text-wrapper-9 {
  position: absolute;
  top: 558px;
  left: 72px;
  width: 242px;
  font-family: "Jost-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
}

iPhone 16 Plus - 1
index.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-plus">
      <img class="sprt" src="img/sprt-1.png" />
      <img class="sec-logo" src="img/sec-logo-01as-1.png" />
      <img class="sec" src="img/sec-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">LOGIN</div>
      <div class="div"></div>
      <div class="text-wrapper-2">REGISTER</div>
    </div>
  </body>
</html>

style.css
.iphone-plus {
  border: 1px solid;
  border-color: #000000;
  background-image: url(./img/iphone-16-plus-1.png);
  background-size: cover;
  background-position: 50% 50%;
  width: 100%;
  min-width: 466px;
  min-height: 849px;
  position: relative;
}

.iphone-plus .sprt {
  position: absolute;
  top: 0;
  left: 0;
  width: 466px;
  height: 849px;
  aspect-ratio: 0.67;
  object-fit: cover;
}

.iphone-plus .sec-logo {
  position: absolute;
  top: 66px;
  left: 9px;
  width: 457px;
  height: 92px;
  aspect-ratio: 4.97;
  object-fit: cover;
}

.iphone-plus .sec {
  position: absolute;
  top: 167px;
  left: 164px;
  width: 133px;
  height: 133px;
  aspect-ratio: 1;
  object-fit: cover;
}

.iphone-plus .rectangle {
  top: 345px;
  height: 57px;
  position: absolute;
  left: 139px;
  width: 188px;
  background-color: #da64c4;
}

.iphone-plus .text-wrapper {
  position: absolute;
  top: 356px;
  left: 173px;
  width: 121px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-plus .div {
  top: 438px;
  height: 51px;
  position: absolute;
  left: 139px;
  width: 188px;
  background-color: #da64c4;
}

.iphone-plus .text-wrapper-2 {
  position: absolute;
  top: 443px;
  left: 149px;
  width: 178px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #100606;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

iPhone Air - 1
index.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-air">
      <img
        class="pngtree-simple-sport"
        src="img/pngtree-simple-sport-colorful-background-picture-image-1065277-1.png"
      />
      <img class="star" src="img/star-3.svg" />
      <img class="img" src="img/star-4.svg" />
      <img class="star-2" src="img/star-5.svg" />
      <img class="star-3" src="img/star-6.svg" />
      <div class="text-wrapper">SPORTS DAY EVENT</div>
      <img class="star-4" src="img/star-1.svg" />
      <img class="star-5" src="img/star.svg" />
      <div class="div">KHO KHO</div>
      <div class="text-wrapper-2">BASKETBALL</div>
      <div class="text-wrapper-3">BADMINTON</div>
      <div class="text-wrapper-4">200M RUNNING</div>
      <div class="text-wrapper-5">4x100 RELAY</div>
      <div class="text-wrapper-6">100M RUNNING</div>
    </div>
  </body>
</html>

style.css
.iphone-air {
  background-color: #ffffff;
  width: 100%;
  min-width: 429px;
  min-height: 849px;
  position: relative;
}

.iphone-air .pngtree-simple-sport {
  position: absolute;
  top: 0;
  left: 0;
  width: 429px;
  height: 849px;
  aspect-ratio: 0.67;
  object-fit: cover;
}

.iphone-air .star {
  top: 413px;
  height: 22px;
  position: absolute;
  left: 55px;
  width: 26px;
}

.iphone-air .img {
  top: 467px;
  height: 22px;
  position: absolute;
  left: 55px;
  width: 26px;
}

.iphone-air .star-2 {
  top: 514px;
  height: 22px;
  position: absolute;
  left: 55px;
  width: 26px;
}

.iphone-air .star-3 {
  top: 567px;
  height: 22px;
  position: absolute;
  left: 55px;
  width: 26px;
}

.iphone-air .text-wrapper {
  position: absolute;
  top: 180px;
  left: 65px;
  width: 343px;
  font-family: "Kalam-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-air .star-4 {
  top: 302px;
  height: 14px;
  position: absolute;
  left: 55px;
  width: 26px;
}

.iphone-air .star-5 {
  position: absolute;
  top: 353px;
  left: 55px;
  width: 26px;
  height: 22px;
}

.iphone-air .div {
  position: absolute;
  top: 298px;
  left: 96px;
  width: 198px;
  font-family: "Kelly Slab-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-air .text-wrapper-2 {
  position: absolute;
  top: 350px;
  left: 96px;
  width: 156px;
  font-family: "Kelly Slab-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-air .text-wrapper-3 {
  position: absolute;
  top: 517px;
  left: 96px;
  width: 139px;
  font-family: "Kelly Slab-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-air .text-wrapper-4 {
  position: absolute;
  top: 566px;
  left: 96px;
  width: 185px;
  font-family: "Kelly Slab-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-air .text-wrapper-5 {
  position: absolute;
  top: 409px;
  left: 96px;
  width: 156px;
  font-family: "Kelly Slab-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-air .text-wrapper-6 {
  position: absolute;
  top: 463px;
  left: 100px;
  width: 213px;
  font-family: "Kelly Slab-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}
```

## OUTPUT:
<img width="1920" height="1080" alt="Screenshot (26)" src="https://github.com/user-attachments/assets/c202e24b-a331-4e0a-a390-a18d74d9bbf2" />



## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
