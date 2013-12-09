Open-Data-Policy---Tricks-and-Tips
==================================


## How to count entries in a data.json file.  
* Open json file in Chrome.  
* Open the browser's console (f12 in chrome)
* enter: 'count entries'

## How to change comma-separated keywords into an array.  
* Open json file in Chrome.  
* Open the browser's console (f12 in chrome)
* enter: 'datajson = JSON.parse(document.body.textContent);'
* enter: 'for ( var i = 0; i < datajson.length; i++) {datajson[i].keyword = datajson[i].keyword.split(",");}'
* enter: 'document.body.textContent = JSON.stringify(datajson);'










