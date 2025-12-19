# Ex09 Event Registration Web Application
## Date:19/12/25

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <div class="frame"><img class="screenshot" src="img/screenshot-2025-12-19-174713-1.png" /></div>
      <img class="img" src="img/screenshot-2025-12-19-175611-1.png" />
      <img class="screenshot-2" src="img/screenshot-2025-12-19-174713-3.png" />
      <img class="logo" src="img/logo-1.png" />
      <img class="screenshot-3" src="img/screenshot-2025-12-19-174713-2.png" />
    </div>
  </body>
</html>
.android-medium {
  background-color: #e19690;
  overflow: hidden;
  width: 100%;
  min-width: 276px;
  min-height: 556px;
  position: relative;
}

.android-medium .frame {
  position: absolute;
  top: -13px;
  left: 1015px;
  width: 317px;
  height: 464px;
  display: flex;
  overflow: hidden;
  transform: rotate(-3.88deg);
}

.android-medium .screenshot {
  margin-top: -391.5px;
  width: 100px;
  height: 146px;
  margin-left: -4557.8px;
  transform: rotate(3.88deg);
  aspect-ratio: 0.68;
  object-fit: cover;
}

.android-medium .img {
  position: absolute;
  top: 150px;
  left: 90px;
  width: 3px;
  height: 1px;
  aspect-ratio: 2.59;
  object-fit: cover;
}

.android-medium .screenshot-2 {
  position: absolute;
  top: 3px;
  left: 0;
  width: 276px;
  height: 550px;
  aspect-ratio: 0.68;
  object-fit: cover;
}

.android-medium .logo {
  position: absolute;
  top: 15px;
  left: 14px;
  width: 247px;
  height: 37px;
  aspect-ratio: 6.65;
  object-fit: cover;
}

.android-medium .screenshot-3 {
  position: absolute;
  top: 98px;
  left: 29px;
  width: 205px;
  height: 53px;
}
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="background" src="img/background-image2-1.png" />
      <div class="text-wrapper">EVENT REGISTRATION FORM</div>
      <img class="text-on-a-path" src="img/text-on-a-path-4.svg" />
      <img class="img" src="img/text-on-a-path-2.svg" />
      <img class="text-on-a-path-2" src="img/image.svg" />
      <img class="text-on-a-path-3" src="img/text-on-a-path-6.svg" />
      <img class="text-on-a-path-4" src="img/text-on-a-path.svg" />
      <div class="rectangle"></div>
      <img class="text-on-a-path-5" src="img/text-on-a-path-3.svg" />
      <img class="text-on-a-path-6" src="img/text-on-a-path-5.svg" />
      <img class="line" src="img/line-1.svg" />
      <p class="REF-NUMBER-NAME">
        REF&nbsp;&nbsp;NUMBER: <br />
        <br />NAME:<br /><br /><br />DEPARTMENT:<br /><br /><br />AGE:<br /><br /><br />GENTER:<br /><br /><br />MOBILE
        NUMBER:<br /><br /><br />EMAIL ID:
      </p>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <div class="rectangle-7"></div>
    </div>
  </body>
</html>
.android-medium {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 312px;
  min-height: 562px;
  position: relative;
}

.android-medium .background {
  position: absolute;
  top: 0;
  left: 0;
  width: 312px;
  height: 547px;
  aspect-ratio: 2;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 48px;
  left: 59px;
  width: 1130px;
  aspect-ratio: 11.53;
  font-family: "Inter-Black", Helvetica;
  font-weight: 900;
  color: #000000;
  font-size: 12px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-on-a-path {
  position: absolute;
  top: 162px;
  left: -3955px;
  width: 136px;
  height: 28px;
}

.android-medium .img {
  position: absolute;
  top: 209px;
  left: -3960px;
  width: 136px;
  height: 33px;
}

.android-medium .text-on-a-path-2 {
  position: absolute;
  top: 288px;
  left: -3955px;
  width: 136px;
  height: 32px;
}

.android-medium .text-on-a-path-3 {
  position: absolute;
  top: 160px;
  left: -3960px;
  width: 138px;
  height: 30px;
}

.android-medium .text-on-a-path-4 {
  position: absolute;
  top: 162px;
  left: -3959px;
  width: 135px;
  height: 28px;
}

.android-medium .rectangle {
  position: absolute;
  top: 281px;
  left: 31px;
  width: 137px;
  height: 30px;
  background-color: #fff9f9;
}

.android-medium .text-on-a-path-5 {
  position: absolute;
  top: 277px;
  left: -3867px;
  width: 140px;
  height: 27px;
}

.android-medium .text-on-a-path-6 {
  position: absolute;
  top: 259px;
  left: -3959px;
  width: 140px;
  height: 32px;
}

.android-medium .line {
  position: absolute;
  top: 345px;
  left: 55px;
  width: 1px;
  height: 1px;
  object-fit: cover;
}

.android-medium .REF-NUMBER-NAME {
  position: absolute;
  top: 121px;
  left: 42px;
  font-family: "Inter-Black", Helvetica;
  font-weight: 900;
  color: #000000;
  font-size: 12px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .div {
  position: absolute;
  top: 136px;
  left: 39px;
  width: 132px;
  height: 19px;
  background-color: #d9d9d9;
}

.android-medium .rectangle-2 {
  position: absolute;
  top: 170px;
  left: 39px;
  width: 132px;
  height: 19px;
  background-color: #d9d9d9;
  transform: rotate(0.25deg);
}

.android-medium .rectangle-3 {
  position: absolute;
  top: 213px;
  left: 39px;
  width: 132px;
  height: 19px;
  background-color: #d9d9d9;
}

.android-medium .rectangle-4 {
  position: absolute;
  top: 259px;
  left: 36px;
  width: 132px;
  height: 19px;
  background-color: #d9d9d9;
}

.android-medium .rectangle-5 {
  position: absolute;
  top: 301px;
  left: 35px;
  width: 132px;
  height: 19px;
  background-color: #d9d9d9;
}

.android-medium .rectangle-6 {
  position: absolute;
  top: 344px;
  left: 35px;
  width: 132px;
  height: 19px;
  background-color: #d9d9d9;
}

.android-medium .rectangle-7 {
  position: absolute;
  top: 388px;
  left: 35px;
  width: 132px;
  height: 19px;
  background-color: #d9d9d9;
  aspect-ratio: 7.11;
}
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="image" src="img/image1-1.png" />
      <div class="background">
        <img class="vector" src="img/image.svg" />
        <img class="img" src="img/vector-2.svg" />
        <img class="vector-2" src="img/vector.svg" />
        <img class="screenshot" src="img/screenshot-2025-12-19-183548-1.png" />
      </div>
      <img class="screenshot-2" src="img/screenshot-2025-12-19-183548-2.png" />
      <img class="screenshot-3" src="img/screenshot-2025-12-19-183548-3.png" />
      <div class="THANK-YOU-YOU-HAVE">THANK YOU <br />YOU HAVE&nbsp;&nbsp;REGISTERED<br />SUCCESSFULLY</div>
      <img class="logo" src="img/logo-2.png" />
      <img class="screenshot-4" src="img/screenshot-2025-12-19-183913-1.png" />
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
    </div>
  </body>
</html>
.android-medium {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 302px;
  min-height: 574px;
  position: relative;
}

.android-medium .image {
  position: absolute;
  top: 7px;
  left: 282px;
  width: 13px;
  height: 18px;
  aspect-ratio: 0.74;
  object-fit: cover;
}

.android-medium .background {
  position: absolute;
  top: 145px;
  left: 62px;
  width: 92px;
  height: 44px;
}

.android-medium .vector {
  position: absolute;
  width: 29.91%;
  height: 29.91%;
  top: 32.43%;
  left: 41.08%;
}

.android-medium .img {
  position: absolute;
  width: 30.61%;
  height: 33.51%;
  top: 41.65%;
  left: 28.26%;
}

.android-medium .vector-2 {
  position: absolute;
  width: 23.50%;
  height: 23.50%;
  top: 30.29%;
  left: 49.62%;
}

.android-medium .screenshot {
  width: 7.61%;
  top: 16px;
  left: 53.26%;
  height: 10px;
  position: absolute;
  aspect-ratio: 0.69;
  object-fit: cover;
}

.android-medium .screenshot-2 {
  top: 239px;
  left: 127px;
  width: 122px;
  height: 177px;
  position: absolute;
  aspect-ratio: 0.69;
  object-fit: cover;
}

.android-medium .screenshot-3 {
  top: 0;
  left: 0;
  width: 302px;
  height: 564px;
  position: absolute;
  aspect-ratio: 0.69;
  object-fit: cover;
}

.android-medium .THANK-YOU-YOU-HAVE {
  position: absolute;
  top: 274px;
  left: 51px;
  width: 231px;
  font-family: "Inter-Black", Helvetica;
  font-weight: 900;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .logo {
  position: absolute;
  top: 7px;
  left: 24px;
  width: 244px;
  height: 37px;
  aspect-ratio: 6.65;
  object-fit: cover;
}

.android-medium .screenshot-4 {
  position: absolute;
  top: 101px;
  left: 64px;
  width: 174px;
  height: 116px;
  aspect-ratio: 1.5;
  object-fit: cover;
}

.android-medium .text-on-a-path {
  position: absolute;
  top: 203px;
  left: -4287px;
  width: 200px;
  height: 49px;
}
```

## OUTPUT:
![alt text](<Screenshot 2025-12-19 201505-1.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
