### Getting Started


RoundSlider is a JavaScript library that runs the calculator sliding function, it's built on top of jqeury as an IIFE. 


## Functions that are used to set the calculations 

// div that holds the whole calculator and the sliding circle 
id="shape"

// number in the middle 
sliderValue; 

// function that calculates each output for weekly and yearly results   
count();

// function that updates calculator number in the middle 
updateSliderValue(); 

// Other slider options that are included to customize 
$(document).ready(function() {
    $("#type").roundSlider({
        svgMode: true,
        value: 45,
    });
    $("#shape").roundSlider({
        svgMode: true,
        value: 10000,      // starting value of the number in the middle 
        startAngle: 90,    // starting angle at the top 
        min: 0,            // minimum value
        max: 100100,       // maximum value in the can reach 
        radius: 150,       // size of the calculator in width and height 
        width: 26,         // width of slider path 
        handleSize: "28",  // handle size 
        animation: true,
        showTooltip: true,
        mouseScrollAction: true,
        handleShape: "round",
        sliderType: "min-range",
        tooltipFormat: "tooltipVal2"
    });
});
function tooltipVal2(args) {
    return "$ " + args.value;  // Dollar sign in front of the value 
}


## Deployment 
initialize the script via <script> tags 
