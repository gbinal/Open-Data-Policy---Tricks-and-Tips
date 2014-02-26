Open-Data-Policy---Tricks-and-Tips
==================================


## How to count entries in a data.json file.  
* Open json file in Chrome.  
* Open the browser's console (f12 in chrome)
* enter: 'count entries'

* [How to change comma-separated keywords into an array](https://github.com/gbinal/Open-Data-Policy---Tricks-and-Tips/blob/master/reformatting_keywords.md)

## Common problems 
* The public data listing automatically downloads instead of opening in the browser.

_The problem is most likely some sort of mime type directives in the web server (apache, etc). You can put in directives in the config for webserver or .htaccess for each site that tells it to handle certain file extensions differently and even specify down to path._


















