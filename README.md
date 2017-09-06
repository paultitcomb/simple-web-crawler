# simple-web-crawler
Simple web crawler that allows you to search a website for a particular word or phrase, and tells you the URL of what page it was found

## To install it

* Git clone this repo to your computer (or download the zip and unzip to a folder)

* in your terminal app cd into the **simple-web-crawler** folder

* type `npm install` to read the package.json file and download the correct dependencies.


## To run a search

* to run a search just type `node crawl.js "Child protection" https://qa.stcdev.com` to run a search for the phrase **child protection** starting at the URL **https://qa.stcdev.com**.

* It will return a set of URLs at the end where this text phrase has been located.