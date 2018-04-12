# Everthread Polo Demo

## Prerequisites

  You'll need a server to save the page. I use expressJS through Node. You can setup your own or use something like python to just run a script.

  If you have node, you need to run 'npm install'

## Deployment

  Using Node, you can just run 'npm run start' or 'node index.js'.

## Documentation
  
  The code is documented inline and everything is pretty straight-forward

## Files
  
### Javascript

  public/js/everthread.js - this is the main js file that does the event handling and requests using jQuery and ajax.

### CSS

  public/css/styles.css - some styling, everything else is done with Bootstrap fetched via CDN.

### STATIC FILES

  public/images/products - static initial white product images.

  index.html - the html page containing the demo.

## To-Do

  For Leandro:

  Right now, we have 2 urls for the image request (v1 and v2). v2, according to Knide (You'll be working with him and Robert for the back-end and the images), is optimized but untested and unmeasured. You'll be doing the testing and the comparison for the two.

  I've labelled where you need to change the codes for the request in the everthread.js file - line 61.

  v1 - https://everthreadapi.com/api/v1/api_thumb_view_db.php
  v2 - https://everthreadapi.com/calibration/preview2.php

