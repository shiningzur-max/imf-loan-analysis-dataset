IMF Loan Data Scraping & Analysis:

This project extracts financial data from the International Monetary Fund website using Selenium and BeautifulSoup. The dataset contains country-wise IMF credit information, including disbursements, repayments, and outstanding balances.

Project Overview:

The goal of this project is to:

Automate data extraction from a dynamic web page

Clean and structure the data for analysis

Store the dataset in a usable format (Excel)

Build a foundation for financial data analysis

Tools & Technologies:

Python

Selenium

BeautifulSoup

Pandas

Jupyter Notebook

Dataset Details:

The dataset includes:

Member (Country Name)

Total IMF Credit Outstanding

Total Disbursements

Total Repayments

Updated Credit Outstanding

File: imf_loans_countries_lists.csv:

How It Works:

Selenium opens the IMF webpage

Page HTML is extracted

BeautifulSoup parses the table data

Data is stored into Python lists

Converted into a Pandas DataFrame

Exported to Excel

How to Run

Install dependencies:

pip install selenium beautifulsoup4 pandas

Run the notebook:

IMP_Loan_Countries_Lists_project_using_selenium.ipynb
Use Cases:

Financial data analysis

Country-level economic insights

Data analyst portfolio project

Web scraping practice

Future Improvements:

Automate multiple date extraction

Add data visualization

Clean numeric values for analysis

Convert into a reusable pipeline

Contributing:

Feel free to fork this repository and improve the project.
