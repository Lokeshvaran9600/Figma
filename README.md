# Ex09 Event Registration Web Application
## Date:30.12.2023

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
Home page

<div style="width: 100%; height: 100%; position: relative; background: #100F0F">
    <img style="width: 304px; height: 43px; left: 33px; top: 50px; position: absolute" src="https://via.placeholder.com/304x43" />
    <div style="width: 304px; height: 47px; left: 33px; top: 294px; position: absolute; background: #D9D9D9"></div>
    <div style="left: 60px; top: 305px; position: absolute; color: #DC0922; font-size: 24px; font-family: Inter; font-weight: 400; word-wrap: break-word">SEC ATHELETICS MEET</div>
    <img style="width: 134px; height: 126px; left: 122px; top: 136px; position: absolute" src="https://via.placeholder.com/134x126" />
    <div style="width: 227px; height: 33px; left: 72px; top: 414px; position: absolute; background: #D9D9D9"></div>
    <div style="left: 103px; top: 418px; position: absolute; color: black; font-size: 24px; font-family: Inter; font-weight: 400; word-wrap: break-word">VIEW DETAILS</div>
</div>

// SEC ATHELETICS MEET
color: #DC0922;
 font-size: 24px;
 font-family: Inter;
 font-weight: 400;
 word-wrap: break-word
---
// VIEW DETAILS
color: black;
 font-size: 24px;
 font-family: Inter;
 font-weight: 400;
 word-wrap: break-word

 Second Page

 <div style="width: 100%; height: 100%; position: relative; background: #191717">
    <img style="width: 328px; height: 49px; left: 24px; top: 44px; position: absolute" src="https://via.placeholder.com/328x49" />
    <div style="width: 334px; height: 379px; left: 18px; top: 153px; position: absolute; background: #D9D9D9"></div>
    <div style="left: 65px; top: 216px; position: absolute; color: black; font-size: 24px; font-family: Inter; font-weight: 400; word-wrap: break-word">4X100 Relay<br/>200m <br/>400m<br/>600m<br/>800m<br/>1500m<br/>Long Jump<br/>High Jump<br/>Shot put <br/>javelin throw</div>
    <div style="width: 373px; height: 42px; left: 18px; top: 166px; position: absolute; color: black; font-size: 24px; font-family: Inter; font-weight: 400; word-wrap: break-word">Availabe sports to participate</div>
    <div style="width: 201px; height: 47px; left: 87px; top: 562px; position: absolute; background: #D9D9D9"></div>
    <div style="left: 129px; top: 571px; position: absolute; color: #6937D3; font-size: 24px; font-family: Inter; font-weight: 400; word-wrap: break-word">REGISTER</div>
</div>

// 4X100 Relay<br/>200m <br/>400m<br/>600m<br/>800m<br/>1500m<br/>Long Jump<br/>High Jump<br/>Shot put <br/>javelin throw
color: black;
 font-size: 24px;
 font-family: Inter;
 font-weight: 400;
 word-wrap: break-word
---
// Availabe sports to participate
color: black;
 font-size: 24px;
 font-family: Inter;
 font-weight: 400;
 word-wrap: break-word
---
// REGISTER
color: #6937D3;
 font-size: 24px;
 font-family: Inter;
 font-weight: 400;
 word-wrap: break-word

 Third Page

 <div style="width: 100%; height: 100%; position: relative; background: #181616">
    <img style="width: 319px; height: 47px; left: 17px; top: 45px; position: absolute" src="https://via.placeholder.com/319x47" />
    <div style="width: 264px; height: 40px; left: 38px; top: 138px; position: absolute; background: #D9D9D9"></div>
    <div style="left: 73px; top: 146px; position: absolute; color: #37B0B0; font-size: 20px; font-family: Inter; font-weight: 400; word-wrap: break-word">REGISTRATION FORM</div>
    <div style="width: 98px; height: 29px; left: 19px; top: 231px; position: absolute; background: #D9D9D9"></div>
    <div style="left: 38px; top: 236px; position: absolute; color: black; font-size: 20px; font-family: Inter; font-weight: 400; word-wrap: break-word">NAME</div>
    <div style="width: 139px; height: 28px; left: 17px; top: 298px; position: absolute; background: #D9D9D9"></div>
    <div style="left: 26px; top: 303px; position: absolute; color: black; font-size: 16px; font-family: Inter; font-weight: 400; word-wrap: break-word">REFERENCE NO</div>
    <div style="width: 115px; height: 24px; left: 17px; top: 356px; position: absolute; background: #D9D9D9"></div>
    <div style="left: 55px; top: 356px; position: absolute; color: black; font-size: 20px; font-family: Inter; font-weight: 400; word-wrap: break-word">DOB</div>
    <div style="width: 207px; height: 25px; left: 9px; top: 413px; position: absolute; background: #D9D9D9"></div>
    <div style="left: 10px; top: 413px; position: absolute; color: black; font-size: 20px; font-family: Inter; font-weight: 400; word-wrap: break-word">INTRESETED SPORTS</div>
    <div style="width: 153px; height: 40px; left: 127px; top: 493px; position: absolute; background: #E21C1C"></div>
    <div style="left: 165px; top: 503px; position: absolute; color: black; font-size: 20px; font-family: Inter; font-weight: 400; word-wrap: break-word">SUBMIT</div>
    <div style="width: 25px; height: 0px; left: 131px; top: 245px; position: absolute; border: 3px #33FF21 solid"></div>
    <div style="width: 25.02px; height: 0px; left: 170px; top: 313px; position: absolute; transform: rotate(-2.29deg); transform-origin: 0 0; border: 2px #2BF11A solid"></div>
    <div style="width: 35.13px; height: 0px; left: 141.94px; top: 366.30px; position: absolute; transform: rotate(0.66deg); transform-origin: 0 0; border: 2px #59FC0C solid"></div>
    <div style="width: 21.10px; height: 0px; left: 230.96px; top: 425.24px; position: absolute; transform: rotate(-1.29deg); transform-origin: 0 0; border: 2px #83F827 solid"></div>
    <div style="width: 165px; height: 25px; left: 171px; top: 235px; position: absolute; background: #D9D9D9"></div>
    <div style="width: 138px; height: 29px; left: 216px; top: 305px; position: absolute; background: #D9D9D9"></div>
    <div style="width: 153px; height: 26px; left: 201px; top: 361px; position: absolute; background: #D9D9D9"></div>
    <div style="width: 100px; height: 22px; left: 261px; top: 415px; position: absolute; background: #D9D9D9"></div>
</div>

// REGISTRATION FORM
color: #37B0B0;
 font-size: 20px;
 font-family: Inter;
 font-weight: 400;
 word-wrap: break-word
---
// NAME
color: black;
 font-size: 20px;
 font-family: Inter;
 font-weight: 400;
 word-wrap: break-word
---
// REFERENCE NO
color: black;
 font-size: 16px;
 font-family: Inter;
 font-weight: 400;
 word-wrap: break-word
---
// DOB
color: black;
 font-size: 20px;
 font-family: Inter;
 font-weight: 400;
 word-wrap: break-word
---
// INTRESETED SPORTS
color: black;
 font-size: 20px;
 font-family: Inter;
 font-weight: 400;
 word-wrap: break-word
---
// SUBMIT
color: black;
 font-size: 20px;
 font-family: Inter;
 font-weight: 400;
 word-wrap: break-word


```
## OUTPUT:
![Alt text](<Screenshot (68).png>)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
