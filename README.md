# Financial-Stock-Analysis-Project

This repo is for my course **Big Data Analysis** in NTUST, designed to extract and analyze stock trading data from the Taiwan Stock Exchange (TWSE) website (台灣證券交易所：https://www.twse.com.tw/zh/) 

1. **Authentication**: Connects to the TWSE website, retrieves necessary session data, and solves the captcha using Optical Character Recognition (OCR).

2. **Data Retrieval**: Downloads the stock trading data in CSV format from the TWSE website.

3. **Data Processing**: Combines and processes the data to calculate metrics such as buy/sell quantities, net purchases, average buy prices, and average sell prices for each brokerage firm.

4. **Analysis and Visualization**: Ranks brokerages based on net purchases and generates a CSV report.


## Requirements
```
pip install pandas
pip install bs4
pip install requests
pip install ddddocr 
Pip istall numpy
pip install six
```

## Output
- output.csv: Raw stock trading data downloaded from the TWSE.
- result.csv: Analyzed and ranked data.
