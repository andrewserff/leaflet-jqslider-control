# Introduction

I recently had a need to limit the data that was showing on a map by date.  So I wanted to have a date slider that would control the data range and I wanted to stick it onto a leaflet map.  I found the nice [jQRangeSlider](http://ghusse.github.com/jQRangeSlider/) jQuery plugin and decided to give that a shot.  

# How it works
You need a few things when adding things to a leaflet map.  
1. You need a Control that you will add to the map.  In the `js` directory, you'll find the jQDataRangeControl.js that is our custom control to add to the map.  
2. You will need a div to add the control to.  Our control adds a div with the id `dateSlider` to the `map`.  
3. You need some styling. Check it out in the `css/app.css` to see how we put the slider in the top right of the map.  
4. You need to configure your map.  

You can see all of the set up in the code.  Everything is laid out in the `index.html`

# Result

You can [try out the example here](http://andrewserff.github.com/leaflet-jqslider-control/)