# Ex09 Event Registration Web Application
## Date:30\04\2024

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
page 1

<div style={{width: 360, height: 640, position: 'relative', background: 'white'}}>
  <img style={{width: 360, height: 55, left: 0, top: 0, position: 'absolute'}} src="https://via.placeholder.com/360x55" />
  <img style={{width: 570, height: 280, left: -124, top: 409, position: 'absolute'}} src="https://via.placeholder.com/570x280" />
  <div style={{width: 360, height: 49, left: 0, top: 101, position: 'absolute', background: '#FF0000'}} />
  <div style={{width: 360, height: 54, left: 16, top: 113, position: 'absolute', color: 'white', fontSize: 28, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>ANNUAL SPORTS DAY</div>
  <div style={{width: 118, height: 39, left: 114.50, top: 281, position: 'absolute', background: '#FF0000'}}></div>
  <div style={{width: 185, height: 40, left: 88, top: 333, position: 'absolute', background: '#FF0000'}} />
  <div style={{width: 123, height: 34, left: 125, top: 283, position: 'absolute', color: 'white', fontSize: 28, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>LOGIN</div>
  <div style={{width: 149, height: 40, left: 111, top: 333, position: 'absolute', color: 'white', fontSize: 28, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>REGISTER</div>
  <img style={{width: 269, height: 138, left: 52, top: 143, position: 'absolute', mixBlendMode: 'multiply'}} src="https://via.placeholder.com/269x138" />
</div>
```
```
page 2

<div style={{width: 360, height: 653, position: 'relative', background: 'white'}}>
  <img style={{width: 600, height: 382, left: -128, top: 84, position: 'absolute'}} src="https://via.placeholder.com/600x382" />
  <div style={{width: 221, height: 24, left: 69, top: 65, position: 'absolute', mixBlendMode: 'hard-light', color: 'black', fontSize: 20, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>SPORTS DAY EVENTS</div>
  <div style={{left: 21, top: 466, position: 'absolute', color: 'black', fontSize: 15, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>FOOTBALL</div>
  <div style={{left: 21, top: 495, position: 'absolute', color: 'black', fontSize: 15, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>KABADDI</div>
  <div style={{left: 21, top: 523, position: 'absolute', color: 'black', fontSize: 15, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>CRICKET</div>
  <div style={{left: 21, top: 552, position: 'absolute', color: 'black', fontSize: 15, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>VOLLEY BALL</div>
  <div style={{left: 21, top: 581, position: 'absolute', color: 'black', fontSize: 15, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>BADMINTON</div>
  <div style={{left: 203, top: 463, position: 'absolute', color: 'black', fontSize: 15, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>100 MTS<br/>200 MTS<br/>400 MTS<br/>LONG JUMP<br/>HIGH JUMP<br/>TRIPLE JUMP<br/>JAVELIN THROW</div>
</div>
```
```
page 3

<div style={{width: 360, height: 653, position: 'relative', background: 'white'}}>
  <img style={{width: 828, height: 866, left: 0, top: -27, position: 'absolute'}} src="https://via.placeholder.com/828x866" />
  <div style={{width: 232, height: 24, left: 79, top: 38, position: 'absolute', color: 'white', fontSize: 30, fontFamily: 'Jomhuria', fontWeight: '400', wordWrap: 'break-word'}}>EVENT REGISTRATION FORM<br/></div>
  <div style={{width: 276, height: 33, left: 32, top: 94, position: 'absolute', background: '#9100B5'}} />
  <div style={{width: 98, height: 25, left: 53, top: 97, position: 'absolute', color: 'white', fontSize: 35, fontFamily: 'Jomhuria', fontWeight: '400', wordWrap: 'break-word'}}>FULL NAME : </div>
  <div style={{width: 279, height: 27, left: 32, top: 137, position: 'absolute', background: '#9100B5'}} />
  <div style={{width: 234, height: 16, left: 53, top: 137, position: 'absolute', color: 'white', fontSize: 35, fontFamily: 'Jomhuria', fontWeight: '400', wordWrap: 'break-word'}}>REGISTER NUMBER :</div>
  <div style={{width: 279, height: 30, left: 32, top: 174, position: 'absolute', background: '#9100B5'}} />
  <div style={{width: 239, height: 33, left: 53, top: 174, position: 'absolute', color: 'white', fontSize: 35, fontFamily: 'Jomhuria', fontWeight: '400', wordWrap: 'break-word'}}>AGE :</div>
  <div style={{width: 276, height: 33, left: 32, top: 222, position: 'absolute', background: '#9100B5'}} />
  <div style={{width: 239, height: 30, left: 53, top: 225, position: 'absolute', color: 'white', fontSize: 35, fontFamily: 'Jomhuria', fontWeight: '400', wordWrap: 'break-word'}}>DEPARTMENT :</div>
  <div style={{width: 273, height: 29, left: 35, top: 272, position: 'absolute', background: '#9100B5'}} />
  <div style={{width: 254, height: 29, left: 53, top: 272, position: 'absolute', color: 'white', fontSize: 35, fontFamily: 'Jomhuria', fontWeight: '400', wordWrap: 'break-word'}}>MOBILE NUMBER :</div>
  <div style={{width: 275, height: 37, left: 32, top: 320, position: 'absolute', background: '#9100B5'}} />
  <div style={{width: 276, height: 37, left: 53, top: 322, position: 'absolute', color: 'white', fontSize: 35, fontFamily: 'Jomhuria', fontWeight: '400', wordWrap: 'break-word'}}>EMAIL ID :</div>
  <div style={{width: 275, height: 31, left: 32, top: 369, position: 'absolute', background: '#9100B5'}} />
  <div style={{width: 257, height: 33, left: 46, top: 371, position: 'absolute', color: 'white', fontSize: 35, fontFamily: 'Jomhuria', fontWeight: '400', wordWrap: 'break-word'}}>EVENTS TO REGISTER :</div>
  <img style={{width: 360, height: 122, left: 0, top: 418, position: 'absolute', boxShadow: '4px 4px 4px ', filter: 'blur(4px)'}} src="https://via.placeholder.com/360x122" />
  <img style={{width: 273, height: 119, left: 38, top: 502, position: 'absolute', mixBlendMode: 'darken'}} src="https://via.placeholder.com/273x119" />
  <div style={{width: 369, height: 49, left: 32, top: 1, position: 'absolute', color: 'white', fontSize: 28, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>ANNUAL SPORTS DAY</div>
  <div style={{width: 78, height: 30, left: 242, top: 397, position: 'absolute', color: 'white', fontSize: 35, fontFamily: 'Jomhuria', fontWeight: '400', wordWrap: 'break-word'}}>SUBMIT </div>
</div>
```
```
page 4

<div style={{width: 360, height: 657, position: 'relative', background: 'white'}}>
  <img style={{width: 360, height: 847, left: 0, top: -85, position: 'absolute'}} src="https://via.placeholder.com/360x847" />
  <div style={{width: 314, height: 55, left: 82, top: 65, position: 'absolute', mixBlendMode: 'hard-light', color: 'white', fontSize: 64, fontFamily: 'Jomhuria', fontWeight: '400', wordWrap: 'break-word'}}>THANK YOU</div>
  <div style={{width: 352, height: 55, left: 32, top: 180, position: 'absolute', color: '#1E1E1E', fontSize: 20, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>Take part in active games to win great prizes</div>
  <div style={{width: 331, height: 62, left: 32, top: 120, position: 'absolute', color: 'white', fontSize: 20, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>INTERNAL STRENGTH FOR EXTERNAL PERFORMANCE</div>
  <div style={{width: 292, height: 35, left: 19, top: 470, position: 'absolute', color: 'black', fontSize: 20, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>CONTACT US :</div>
  <div style={{width: 302, height: 27, left: 25, top: 505, position: 'absolute', color: 'black', fontSize: 20, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>EMAIL : saveetha@gmail.com<br/><br/>@gmail.com<br/></div>
  <div style={{width: 303, height: 24, left: 25, top: 543, position: 'absolute', color: 'black', fontSize: 20, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>MOBILE NO :9876543210</div>
  <img style={{width: 360, height: 46, left: 0, top: 0, position: 'absolute'}} src="https://via.placeholder.com/360x46" />
</div>
```



## OUTPUT:
![alt text](<Screenshot (41).png>)
![alt text](<Screenshot (42).png>)
![alt text](<Screenshot (43).png>)
![alt text](<Screenshot (44).png>)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
