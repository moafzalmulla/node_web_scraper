# node_web_scraper

## Situation
- A web scraper for built in node that outputs scrape data in json objects
- This awesome example uses IMDB website and was orginally posted by Scotch.io: https://scotch.io/tutorials/scraping-the-web-with-node-js
- Due to IMDB site frontend element updates - orginal script sadly didnt work anymore.
- In this Repo I have resolved all bugs and updated the fetch criteria to match any new classes etc to enable the script to work as of February 2019
- Things might change again if IMDB hires a new front end dev :) , but till then we should be ok 

## Deliverable
- Once the script is run, it produces a file called output.json which will contain, scraped data in a json format.

## Get started
- Clone repo
- Npm install
- Go to http://localhost:3000 ( Originaly example uses port 8081, but I like 3000 ;) )
- Run : node server.js
- Open http://localhost:3000 and click the button to scrape 
- The script will on default fetch the data for the movie Glass(2019): https://www.imdb.com/title/tt6823368/ , create a new file called output.json
- The newly created file will have a json object with the data scrape payload.
- Done

### A Note on Web Scraping
Web scraping falls within a gray area of the law. Scraping data for personal use within limits is generally ok but you should always get permission from the website owner before doing so. Our example here was very minimalistic in a sense (we only made one request to IMDB) so that it does not interfere with IMDB's operations. Please scrape responsibly.


PS.

- Once again thanks to Scotch.io for this awesome script
- Also thanks to Sky Ham who spotted the bug initially and posted a fix in the comments
- If you have any issues implementin this script, hit me up on twitter below - I should get back to you fairly quickly

>For the love of code - [@tweetzal](https://twitter.com/tweetzal)
