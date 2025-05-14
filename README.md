# Ex09 Event Registration Web Application
## Date:14.05.2025

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
Page1
<div style="width: 393px; height: 852px; position: relative; background: white; overflow: hidden">
  <img style="width: 563px; height: 955px; left: -119px; top: -52px; position: absolute" src="https://placehold.co/563x955" />
  <img style="width: 539px; height: 108px; left: 0px; top: 6px; position: absolute" src="https://placehold.co/539x108" />
  <img style="width: 225px; height: 224px; left: 84px; top: 114px; position: absolute; border-radius: 100px; border: 1px white solid" src="https://placehold.co/225x224" />
  <div style="width: 278px; height: 67px; left: 87px; top: 338px; position: absolute; color: black; font-size: 32px; font-family: Koulen; font-weight: 400; word-wrap: break-word">SPORTS DAY EVENTS</div>
  <div style="width: 201px; height: 75px; left: 96px; top: 405px; position: absolute; opacity: 0.80; background: black; border-radius: 50px"></div>
  <div style="width: 201px; height: 75px; left: 96px; top: 510px; position: absolute; opacity: 0.80; background: black; border-radius: 50px"></div>
  <div style="width: 97px; height: 29px; left: 160px; top: 428px; position: absolute; color: white; font-size: 24px; font-family: Inria Sans; font-weight: 400; word-wrap: break-word">LOGIN</div>
  <div style="width: 136px; height: 30px; left: 141px; top: 533px; position: absolute; color: white; font-size: 24px; font-family: Inria Sans; font-weight: 400; word-wrap: break-word">REGISTER</div>
</div>
import React from "react";
import styled from "styled-components";

const StyledScreenshot202505140516031 = styled.div`
  width: 563px;
  height: 955px;
  left: -119px;
  top: -52px;
  position: absolute;
`;

const StyledSeclabel1 = styled.div`
  width: 539px;
  height: 108px;
  left: 0px;
  top: 6px;
  position: absolute;
`;

const StyledSeclogo1 = styled.div`
  width: 225px;
  height: 224px;
  left: 84px;
  top: 114px;
  position: absolute;
  border-radius: 100px;
  border: 1px white solid;
`;

const StyledSportsdayeventsspan = styled.span`
  color: black;
  font-size: 32px;
  font-family: Koulen;
  font-weight: 400;
  word-wrap: break-word;
`;

const StyledRectangle1 = styled.div`
  width: 201px;
  height: 75px;
  left: 96px;
  top: 405px;
  position: absolute;
  opacity: 0.80;
  background: black;
  border-radius: 50px;
`;

const StyledRectangle2 = styled.div`
  width: 201px;
  height: 75px;
  left: 96px;
  top: 510px;
  position: absolute;
  opacity: 0.80;
  background: black;
  border-radius: 50px;
`;

const StyledLoginspan = styled.span`
  color: white;
  font-size: 24px;
  font-family: Inria Sans;
  font-weight: 400;
  word-wrap: break-word;
`;

const StyledRegisterspan = styled.span`
  color: white;
  font-size: 24px;
  font-family: Inria Sans;
  font-weight: 400;
  word-wrap: break-word;
`;

const StyledIPhone1415Pro1 = styled.div`
  width: 393px;
  height: 852px;
  position: relative;
  background: white;
  overflow: hidden;
`;

export const Iphone1415Pro1 = () => {
  return (
    <StyledIPhone1415Pro1>
      <StyledScreenshot202505140516031  src="https://placehold.co/563x955"/>
      <StyledSeclabel1  src="https://placehold.co/539x108"/>
      <StyledSeclogo1  src="https://placehold.co/225x224"/>
      <StyledSPORTSDAYEVENTS>SPORTS DAY EVENTS</StyledSPORTSDAYEVENTS>
      <StyledRectangle1 />
      <StyledRectangle2 />
      <StyledLOGIN>LOGIN</StyledLOGIN>
      <StyledREGISTER>REGISTER</StyledREGISTER>
    </StyledIPhone1415Pro1>
  );
};
Page 2
<div style="width: 393px; height: 852px; position: relative; background: white; overflow: hidden">
  <img style="width: 640px; height: 853px; left: -142px; top: 0px; position: absolute" src="https://placehold.co/640x853" />
  <div style="width: 201px; height: 75px; left: -343.50px; top: 505.50px; position: absolute; opacity: 0.80; background: black; border-radius: 50px"></div>
  <div style="width: 332px; height: 73px; left: 31px; top: 52px; position: absolute; color: black; font-size: 32px; font-family: Instrument Sans; font-weight: 400; word-wrap: break-word">SPORTS DAY EVENTS</div>
  <div style="width: 203px; height: 205px; left: -49px; top: -20px; position: absolute; opacity: 0.30; background: #D9D9D9; border-radius: 9999px"></div>
  <div style="width: 203px; height: 205px; left: 95px; top: -25px; position: absolute; opacity: 0.30; background: #D9D9D9; border-radius: 9999px"></div>
  <div style="width: 203px; height: 205px; left: 248px; top: -20px; position: absolute; opacity: 0.30; background: #D9D9D9; border-radius: 9999px"></div>
  <div style="width: 366px; height: 425px; left: 7px; top: 125px; position: absolute; text-align: center; color: #1F06FF; font-size: 20px; font-family: Instrument Sans; font-weight: 400; word-wrap: break-word">Football (Soccer)<br/><br/>Cricket<br/><br/>Basketball<br/><br/>Tennis<br/><br/>Volleyball<br/><br/>Baseball<br/><br/>Badminton (Outdoor)<br/><br/>Cycling<br/><br/>Running<br/><br/>Swimming (Open Water)</div>
</div>
import React from "react";
import styled from "styled-components";

const StyledTheEighteenthAsianGamesPosters = styled.div`
  width: 640px;
  height: 853px;
  left: -142px;
  top: 0px;
  position: absolute;
`;

const StyledRectangle2 = styled.div`
  width: 201px;
  height: 75px;
  left: -343.50px;
  top: 505.50px;
  position: absolute;
  opacity: 0.80;
  background: black;
  border-radius: 50px;
`;

const StyledSportsdayeventsspan = styled.span`
  color: black;
  font-size: 32px;
  font-family: Instrument Sans;
  font-weight: 400;
  word-wrap: break-word;
`;

const StyledEllipse1 = styled.div`
  width: 203px;
  height: 205px;
  left: -49px;
  top: -20px;
  position: absolute;
  opacity: 0.30;
  background: #D9D9D9;
  border-radius: 9999px;
`;

const StyledEllipse2 = styled.div`
  width: 203px;
  height: 205px;
  left: 95px;
  top: -25px;
  position: absolute;
  opacity: 0.30;
  background: #D9D9D9;
  border-radius: 9999px;
`;

const StyledEllipse3 = styled.div`
  width: 203px;
  height: 205px;
  left: 248px;
  top: -20px;
  position: absolute;
  opacity: 0.30;
  background: #D9D9D9;
  border-radius: 9999px;
`;

const StyledFootballsoccercricketbasketballtennisvolleyballbaseballbadmintonoutdoorcyclingrunningswimmingopenwaterspan = styled.span`
  color: #1F06FF;
  font-size: 20px;
  font-family: Instrument Sans;
  font-weight: 400;
  word-wrap: break-word;
`;

const StyledIPhone1415Pro2 = styled.div`
  width: 393px;
  height: 852px;
  position: relative;
  background: white;
  overflow: hidden;
`;

export const Iphone1415Pro2 = () => {
  return (
    <StyledIPhone1415Pro2>
      <StyledTheEighteenthAsianGamesPosters  src="https://placehold.co/640x853"/>
      <StyledRectangle2 />
      <StyledSPORTSDAYEVENTS>SPORTS DAY EVENTS</StyledSPORTSDAYEVENTS>
      <StyledEllipse1 />
      <StyledEllipse2 />
      <StyledEllipse3 />
      <StyledFootballSoccerCricketBasketballTennisVolleyballBaseballBadmintonOutdoorCyclingRunningSwimmingOpenWater>Football (Soccer)<br/><br/>Cricket<br/><br/>Basketball<br/><br/>Tennis<br/><br/>Volleyball<br/><br/>Baseball<br/><br/>Badminton (Outdoor)<br/><br/>Cycling<br/><br/>Running<br/><br/>Swimming (Open Water)</StyledFootballSoccerCricketBasketballTennisVolleyballBaseballBadmintonOutdoorCyclingRunningSwimmingOpenWater>
    </StyledIPhone1415Pro2>
  );
};
Page 3
<div style="width: 393px; height: 852px; position: relative; background: white; overflow: hidden">
  <img style="width: 640px; height: 853px; left: -96px; top: -1px; position: absolute" src="https://placehold.co/640x853" />
  <div style="width: 228px; height: 39px; left: 83px; top: 47px; position: absolute; text-align: center; color: #5E00FF; font-size: 20px; font-family: Jockey One; font-weight: 400; word-wrap: break-word">EVENT REGISTRATION FORM</div>
  <div style="left: 101px; top: 77px; position: absolute; text-align: center; color: black; font-size: 13px; font-family: Jockey One; font-weight: 400; word-wrap: break-word">Fill the form</div>
  <div style="width: 201px; height: 75px; left: -343.50px; top: 505.50px; position: absolute; opacity: 0.80; background: black; border-radius: 50px"></div>
  <div style="width: 243px; height: 42px; left: 55px; top: 122px; position: absolute; background: white; border-radius: 10px; border: 1px black solid"></div>
  <div style="width: 243px; height: 42px; left: 55px; top: 566px; position: absolute; background: #FFF9F9; border-radius: 10px; border: 1px black solid"></div>
  <div style="width: 243px; height: 50px; left: 55px; top: 640px; position: absolute; background: #2EEFCF; border-radius: 10px; border: 1px #FF0000 solid"></div>
  <div style="width: 243px; height: 42px; left: 55px; top: 514px; position: absolute; background: #FFFBFB; border-radius: 10px; border: 1px black solid"></div>
  <div style="width: 243px; height: 42px; left: 55px; top: 455px; position: absolute; background: white; border-radius: 10px; border: 1px black solid"></div>
  <div style="width: 243px; height: 42px; left: 55px; top: 396px; position: absolute; background: white; border-radius: 10px; border: 1px black solid"></div>
  <div style="width: 243px; height: 42px; left: 55px; top: 344px; position: absolute; background: white; border-radius: 10px; border: 1px black solid"></div>
  <div style="width: 243px; height: 42px; left: 55px; top: 233px; position: absolute; background: white; border-radius: 10px; border: 1px black solid"></div>
  <div style="width: 243px; height: 42px; left: 55px; top: 289px; position: absolute; background: white; border-radius: 10px; border: 1px black solid"></div>
  <div style="width: 243px; height: 42px; left: 55px; top: 181px; position: absolute; background: white; border-radius: 10px; border: 1px black solid"></div>
  <div style="left: 83px; top: 133px; position: absolute; text-align: center; color: black; font-size: 14px; font-family: Jockey One; font-weight: 400; word-wrap: break-word">Full name</div>
  <div style="left: 83px; top: 196px; position: absolute; text-align: center; color: black; font-size: 14px; font-family: Jockey One; font-weight: 400; word-wrap: break-word">Gender</div>
  <div style="left: 83px; top: 244px; position: absolute; text-align: center; color: black; font-size: 14px; font-family: Jockey One; font-weight: 400; word-wrap: break-word">Age</div>
  <div style="left: 82px; top: 299px; position: absolute; text-align: center; color: black; font-size: 14px; font-family: Jockey One; font-weight: 400; word-wrap: break-word">Registration number</div>
  <div style="left: 83px; top: 355px; position: absolute; text-align: center; color: black; font-size: 14px; font-family: Jockey One; font-weight: 400; word-wrap: break-word">Number of team members</div>
  <div style="left: 83px; top: 407px; position: absolute; text-align: center; color: black; font-size: 14px; font-family: Jockey One; font-weight: 400; word-wrap: break-word">Department</div>
  <div style="left: 82px; top: 466px; position: absolute; text-align: center; color: black; font-size: 14px; font-family: Jockey One; font-weight: 400; word-wrap: break-word">Mobile number</div>
  <div style="left: 82px; top: 521px; position: absolute; text-align: center; color: black; font-size: 14px; font-family: Jockey One; font-weight: 400; word-wrap: break-word">Email id</div>
  <div style="left: 83px; top: 577px; position: absolute; text-align: center; color: black; font-size: 14px; font-family: Jockey One; font-weight: 400; word-wrap: break-word">Event of registration</div>
  <div style="left: 142px; top: 651px; position: absolute; text-align: center; color: black; font-size: 20px; font-family: Jockey One; font-weight: 400; word-wrap: break-word">REGISTER</div>
</div>
Page4
<div style="width: 393px; height: 852px; position: relative; background: white; overflow: hidden">
  <img style="width: 640px; height: 853px; left: -247px; top: 0px; position: absolute" src="https://placehold.co/640x853" />
  <div style="width: 201px; height: 75px; left: -343.50px; top: 505.50px; position: absolute; opacity: 0.80; background: black; border-radius: 50px"></div>
  <img style="width: 532px; height: 107px; left: -8px; top: 15px; position: absolute" src="https://placehold.co/532x107" />
  <div style="width: 195px; height: 57px; left: 99px; top: 150px; position: absolute; text-align: center; color: black; font-size: 36px; font-family: Jockey One; font-weight: 400; word-wrap: break-word">THANK YOU</div>
  <div style="width: 195px; height: 57px; left: 99px; top: 218px; position: absolute; text-align: center; color: black; font-size: 14px; font-family: Jockey One; font-weight: 400; word-wrap: break-word">All the Best to All Participants! 🌟<br/>Dear Champions,<br/>Wishing you all the very best as you step onto the field to showcase your talent, teamwork, and sportsmanship at the Saveetha Engineering College Sports Events. Remember, every game is an opportunity to learn, grow, and shine.<br/>Play with passion, respect your opponents, and enjoy every moment of the competition. Winning is important, but giving your best effort and creating memorable experiences is what truly counts.<br/>🏆 Stay strong.    ⚡ Stay focused.    💪 Stay positive.<br/>Good luck to all! Make your college proud!</div>
</div>
```
## OUTPUT:
![alt text](<Screenshot 2025-05-14 092029.png>)
## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
