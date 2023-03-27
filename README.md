## Getting Started


#### RoundSlider is a JavaScript library that runs the calculator sliding function. It's built on top of jQuery as an IIFE. 
<br />

### Round Slider
Div that holds the whole calculator with the sliding circle 
- id="shape"

Number in the middle 
- sliderValue; 

Function that calculates each output for weekly and yearly results   
- count();

Function that updates calculator number in the middle 
- updateSliderValue(); 

<br />

### Updating scripts and deploying  

This script needs to be used externally with Webflow, because Webflow has a limitation of 10,000 characters and this library exceeds that. Every time you make changes, update script tags url for it to be functioning properly, in the steps provided below:

- Select the repository you want to use and copy the url, for example: https://github.com/on-associates/atob-webflow-scripts/blob/main/roundslider.min.js 
- Open this link: [raw.githack](https://raw.githack.com) and paste the url to create a cdn.
- Insert the production url between the <script src=""></script> tags in Webflow.
