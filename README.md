## Getting Started


RoundSlider is a JavaScript library that runs the calculator sliding function, it's built on top of jQuery as an IIFE. 

<br>
### Functions that are used to set the calculations 

Div that holds the whole calculator with the sliding circle 
- id="shape"

Number in the middle 
- sliderValue; 

Function that calculates each output for weekly and yearly results   
- count();

Function that updates calculator number in the middle 
- updateSliderValue(); 


<br>
### Updating the script and deploying  

This script needs to be used externally with Webflow, because Webflow has a limitation of 10,000 characters and this library exceeds that. Every time you make changes, update the url for it to be functioning properly in the steps provided below 

- Select the repository you want to use, for example ; https://github.com/on-associates/atob-webflow-scripts/blob/main/roundslider.min.js 
- Run through JSDelivr to create a cdn - https://www.jsdelivr.com/github 
- Use that output between the <script src=""></script> tags inside of Webflow 
