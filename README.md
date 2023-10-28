# Project: Web scraping utilizing Google Cloud API to extract companies' listed contact emails


## 1. Objective

The objective of this project is to scrape company emails using Google Cloud API and Google Search to collect data. The project accepts a Google Sheet input with names of company of interest and returns their website links and contact emails. This tool is helpful for those who want to obtain organization emails on a large scale. 

DISCLAIMER: The tool should not be used to produce spam emails or disturb recipients. 

## 2. Demonstration
Input:
<img width="1791" alt="InputSheet" src="https://github.com/tainguyen103/EmailScraping/assets/108405800/dd472539-90ba-40c4-aece-ce1a34de8eb7">

Output:
<img width="1791" alt="OutputSheet" src="https://github.com/tainguyen103/EmailScraping/assets/108405800/0171f5b4-d129-4ebe-924f-987d2fd26630">


## 3. Process
Steps that were carried out in the project:

- Obtain a Google Sheet API authorization through Google Cloud API
<img width="1791" alt="Screenshot 2023-10-27 at 23 37 35" src="https://github.com/tainguyen103/EmailScraping/assets/108405800/9d34a020-9967-4da2-92de-5dbb0e0075b1">

- Scrape company websites and emails utilizing serenium and Python
  
- Update the Google Sheet with information found


## 4. Tools

To run the code, you need to have the following installed on your machine:

- Python 3
- Selenium
- Pandas

## 5. Programming Report 
The code report can be found in the report.ipynb file in the root directory of the project.


## 6. Contributor
Tai Nguyen
