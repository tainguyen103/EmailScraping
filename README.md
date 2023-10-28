# Project: Web scraping utilizing Google Cloud API to extract companies' listed contact emails


## 1. Objective

The goal of this project is to leverage the Google Cloud API and Google Search to retrieve company email addresses. The project is designed to process a Google Sheet input containing the names of specific companies and, in return, provide their website links and contact email information. This tool proves valuable for individuals seeking to acquire organization email data on a broader scale.

DISCLAIMER: Please note that this tool should not be utilized for generating spam emails or causing disruption to recipients.

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

The following modules and packages were used in the implementation of this project:

- Python 3
- BeautifulSoup4
- Selenium
- Pandas
- Google Colab

## 5. Programming Report 
The code report can be found in the Report.ipynb file in the root directory of the project.


## 6. Contributor
Tai Nguyen
