# GOAL 
Gather data from the top companies listed in Business Directory for all countries and industries possible.
This data will be used to make a market report and projections for strategic planning of business. 
  
For each company we need:
  - Company name
  - State
  - Country
  - Full address
  - Website 
  - Phone Number
  - Annual Sales
  - Line of Business
  - Number of Employees

## PROCESS: 
Getting the data needed is a 2-part step. We would need to extract the list of the companies from a directory and extract
initial information from the same website and then log in into Finance Analytics account for further company information.

Scraping Part 1: 
 - For this repo, we have a list of companies for Medical Equipment and Supplies Manufacturing industry in China. 
   So, we extract every company name, state in which the company is located, and the DnB directory link 
   in every page of directory.
 - We would go through every DnB directory link as this will lead us into the company's address and website.
 - For this part we will have the companies name, state, country, address, and the company website.


![DnB Part1](https://github.com/marizethpb/DnB-Webscraping-for-Market-Report/assets/79640443/dc5cf6ca-6bd4-4308-9183-8661b642c108)

Scraping Part 2: 
 - For this part, we will log in into DnB Finance Analytics to get the remaining details we need. 
 - Then we search every company in Scraping Part 1. We will use advanced search for this to 
   essentially make the company float firstly on search result.
 - This step will rely heavily on web automation to scrape data.
 - After all the data is gathered, we will consolidate Scraping Parts 1 & 2
   and export it to excel file.

![DnB Part2](https://github.com/marizethpb/DnB-Webscraping-for-Market-Report/assets/79640443/130e76a9-4d62-40bb-8171-bb36e4c20b78)


### Did this first on Power Automate then tried doing it in Python too because:
  - not much flexibility on extraction by pages
  - I can't use my laptop when I run the flow
  - python is fun
