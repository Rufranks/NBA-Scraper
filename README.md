# NBA-Scraper

This code scrapes https://sports.tipico.com/de for their NBA moneyline odds and the spread too.

It compiles the team name, ML odds and the Spread into a dataframe using pandas and writes this dataframe to a .csv file for further use. 
I use it for my NBA betting model. 

This code uses selenium, so a driver is necessarry for your browser of choice. 

Next addition to this scraper is to automate it to scrape without me having to use the terminal each time to run the script. 
+ can look to include a few lines to grab the o/u lines, but my model isnt concerned with this at the moment
