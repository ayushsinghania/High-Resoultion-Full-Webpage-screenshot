# High-Resoultion-Full-Webpage-screenshot
Use Node.js and Google's Puppeteer API to take High Res screenshot of complete webpage (multiple URL's) and save it.

## About Puppeteer

https://github.com/GoogleChrome/puppeteer

## Requirement
1. Install nodejs needed to run the code from - https://nodejs.org/en/
    ~~~sh
    $ npm i puppeteer
    ~~~
 * Caution! - Puppeteer requires at least Node v6.4.0, but the code written uses async/await which is only supported in Node v7.6.0 or greater.
2. Scrape the name and url's of the webpages to be captured and save it in a json format.
3. Copy the content of json file and paste it inside const urls = [ ];

## How to run

The __getScreenShots.js__ script(+ some others) are included .

~~~sh
$  node <code_name>.js
~~~
* - You can also specify the resolution of your screenshot inside the code.

## Results

The code will take the url and take high resolution screenshot and save it insided a newly created folder (name can be altered inside the code).
