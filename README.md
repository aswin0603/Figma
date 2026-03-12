# Ex09 Event Registration Web Application
## Date: 12-03-2025

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
### HTML
```html
<!DOCTYPE html>
<html lang="en">
   <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <meta name="description" content="Exported from Figma">
      <title>Exported Figma Design</title>
      <link href="https://fonts.googleapis.com/css?family=Inter&display=swap" rel="stylesheet">
      <link rel="stylesheet" href="styles.css">
   </head>
   <body>
      <div class="events-1">
         <div class="status-bar-2">
            <div class="right-side-3">
               <div class="battery-4">
                  <img src="images/rectangle-5.svg" class="rectangle-5" alt="rectangle" />
                  <img src="images/combined-shape-6.svg" class="combined-shape-6" alt="combined-shape" />
                  <img src="images/rectangle-7.svg" class="rectangle-7" alt="rectangle" />
               </div>
               <img src="images/wifi-8.svg" class="wifi-8" alt="wifi" />
               <img src="images/mobile-signal-9.svg" class="mobile-signal-9" alt="mobile-signal" />
            </div>
            <div class="left-side-10">
               <div class="time-11">
                  <img src="images/9-41-12.svg" class="9-41-12" alt="9-41" />
               </div>
            </div>
         </div>
         <img src="images/node-13.png" class="node-13" alt="pexels-vishnurnair-1105666-1" />
         <p class="text-14"><span class="text-white">Events Available</span></p>
         <div class="rectangle-1-15"></div>
         <div class="rectangle-1-16"></div>
         <div class="rectangle-1-17"></div>
         <div class="rectangle-1-18"></div>
         <div class="rectangle-1-19"></div>
         <div class="rectangle-1-20"></div>
         <div class="rectangle-1-21"></div>
         <div class="rectangle-1-22"></div>
         <p class="text-23"><span class="text-rgb-94-79-82">Cricket</span></p>
         <p class="text-24"><span class="text-rgb-94-79-82">Basketball</span></p>
         <p class="text-25"><span class="text-rgb-94-79-82">Volleyball</span></p>
         <p class="text-26"><span class="text-rgb-94-79-82">Badminton</span></p>
         <p class="text-27"><span class="text-rgb-94-79-82">100MTS</span></p>
         <p class="text-28"><span class="text-rgb-94-79-82">200MTS</span></p>
         <p class="text-29"><span class="text-rgb-94-79-82">400MTS</span></p>
         <p class="text-30"><span class="text-rgb-94-79-82">4*100 Relay</span></p>
      </div>
   </body>
</html>
```

### CSS
```css
:root {
  --font-family-inter: 'Inter', sans-serif;
  --text-white: rgba(255, 255, 255, 1);
  --text-rgb-94-79-82: rgba(94, 79, 82, 1);
  --text-black: rgba(0, 0, 0, 0.5);
}

.text-white {
  color: var(--text-white);
}

.text-rgb-94-79-82 {
  color: var(--text-rgb-94-79-82);
}

.text-black {
  color: var(--text-black);
}

/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

/* Prototype Links */
a.prototype-link {
  text-decoration: none;
  color: inherit;
  display: contents;
}

.rectangle-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border: 1px solid rgba(0, 0, 0, 1);
  border-radius: 2.6666667461395264px;
  opacity: 0.3499999940395355;
  border: none;
  outline: none;
}

.combined-shape-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  opacity: 0.4000000059604645;
  fill: rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.rectangle-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 1.3333333730697632px;
  fill: rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.battery-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.wifi-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.mobile-signal-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.right-side-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.9-41-12 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.time-11 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 32px;
}

.left-side-10 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.status-bar-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.node-13 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  opacity: 0.75;
  width: 100%;
  height: auto;
}

.text-14 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 25px;
  line-height: 139.9999976158142%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.rectangle-1-15 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
  border-radius: 7px;
}

.rectangle-1-16 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
  border-radius: 7px;
}

.rectangle-1-17 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
  border-radius: 7px;
}

.rectangle-1-18 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
  border-radius: 7px;
}

.rectangle-1-19 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
  border-radius: 7px;
}

.rectangle-1-20 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
  border-radius: 7px;
}

.rectangle-1-21 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
  border-radius: 7px;
}

.rectangle-1-22 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
  border-radius: 7px;
}

.text-23 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 20px;
  line-height: 139.9999976158142%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-94-79-82);
}

.text-24 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 20px;
  line-height: 139.9999976158142%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-94-79-82);
}

.text-25 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 20px;
  line-height: 139.9999976158142%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-94-79-82);
}

.text-26 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 20px;
  line-height: 139.9999976158142%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-94-79-82);
}

.text-27 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 20px;
  line-height: 139.9999976158142%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-94-79-82);
}

.text-28 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 20px;
  line-height: 139.9999976158142%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-94-79-82);
}

.text-29 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 20px;
  line-height: 139.9999976158142%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-94-79-82);
}

.text-30 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 20px;
  line-height: 139.9999976158142%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-94-79-82);
}

.events-1 {
@media (max-width: 1440px) {
  .events-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .events-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}

.rectangle-35 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border: 1px solid rgba(0, 0, 0, 1);
  border-radius: 2.6666667461395264px;
  opacity: 0.3499999940395355;
  border: none;
  outline: none;
}

.combined-shape-36 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  opacity: 0.4000000059604645;
  fill: rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.rectangle-37 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 1.3333333730697632px;
  fill: rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.battery-34 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.wifi-38 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.mobile-signal-39 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.right-side-33 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.9-41-42 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.time-41 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 32px;
}

.left-side-40 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.status-bar-32 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.node-43 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  opacity: 0.75;
  width: 100%;
  height: auto;
}

.text-44 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 30px;
  line-height: 139.9999976158142%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.registration-31 {
@media (max-width: 1440px) {
  .registration-31 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .registration-31 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}

.rectangle-49 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border: 1px solid rgba(0, 0, 0, 1);
  border-radius: 2.6666667461395264px;
  opacity: 0.3499999940395355;
  border: none;
  outline: none;
}

.combined-shape-50 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  opacity: 0.4000000059604645;
  fill: rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.rectangle-51 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 1.3333333730697632px;
  fill: rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.battery-48 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.wifi-52 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.mobile-signal-53 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.right-side-47 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.9-41-56 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.time-55 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 32px;
}

.left-side-54 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.status-bar-46 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.node-57 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  opacity: 0.75;
  width: 100%;
  height: auto;
}

.text-59 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 20px;
  line-height: 139.9999976158142%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-1-60 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(89, 76, 80, 1);
  border-radius: 7px;
}

.rectangle-2-61 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(140, 97, 89, 1);
  border-radius: 7px;
}

.text-62 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 20px;
  line-height: 139.9999976158142%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.text-63 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 20px;
  line-height: 139.9999976158142%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.group-1-58 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.text-64 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 20px;
  line-height: 139.9999976158142%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.login-page-45 {
@media (max-width: 1440px) {
  .login-page-45 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .login-page-45 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}

.rectangle-69 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border: 1px solid rgba(0, 0, 0, 1);
  border-radius: 2.6666667461395264px;
  opacity: 0.3499999940395355;
  border: none;
  outline: none;
}

.combined-shape-70 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  opacity: 0.4000000059604645;
  fill: rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.rectangle-71 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 1.3333333730697632px;
  fill: rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.battery-68 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.wifi-72 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.mobile-signal-73 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.right-side-67 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.9-41-76 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.time-75 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 32px;
}

.left-side-74 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.status-bar-66 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.node-77 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  opacity: 0.75;
  width: 100%;
  height: auto;
}

.text-78 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 30px;
  line-height: 139.9999976158142%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.text-79 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 20px;
  line-height: 139.9999976158142%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.rectangle-1-80 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
  border-radius: 7px;
}

.text-81 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-inter);
  font-weight: 500;
  font-size: 11px;
  line-height: 139.9999976158142%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-1-82 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
  border-radius: 7px;
}

.text-83 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-inter);
  font-weight: 500;
  font-size: 11px;
  line-height: 139.9999976158142%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-1-84 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
  border-radius: 7px;
}

.rectangle-2-85 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
  border-radius: 7px;
}

.text-86 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-inter);
  font-weight: 500;
  font-size: 11px;
  line-height: 139.9999976158142%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-87 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-inter);
  font-weight: 500;
  font-size: 11px;
  line-height: 139.9999976158142%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-1-88 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
  border-radius: 7px;
}

.text-89 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-inter);
  font-weight: 500;
  font-size: 11px;
  line-height: 139.9999976158142%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-1-90 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
  border-radius: 7px;
}

.text-91 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-inter);
  font-weight: 500;
  font-size: 11px;
  line-height: 139.9999976158142%;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.registration-65 {
@media (max-width: 1440px) {
  .registration-65 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .registration-65 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}

```

## OUTPUT:
<img width="1068" height="553" alt="image" src="https://github.com/user-attachments/assets/fae45a21-432a-4e60-8527-b603364829d2" />


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.

### Name : ASWIN B   
### Register Number : 212224110007
