# House Price Prediction with EmlakJet Data Scraping

## Project Overview
This project involves scraping approximately 15,000 house listings from the EmlakJet website, specifically focusing on properties located in Istanbul. The scraping was conducted using **Selenium**, a powerful web automation tool. The dataset generated from this process can be used for various data analysis or machine learning tasks, including house price prediction.

This repository serves as a resource for those interested in gathering real estate data using Python and applying it to predictive models.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Data Scraping](#data-scraping)
- [Collected Features](#collected-features)
- [Usage](#usage)
- [Requirements](#requirements)
- [Kaggle Notebook](#kaggle-notebook)
- [Contact](#contact)

## Dataset
The dataset was scraped from the EmlakJet website and contains approximately 15,000 house listings, all located in **Istanbul**. Each listing includes information such as property size, number of rooms, heating type, and the price.

### Collected Features:
The following features were collected from each house listing:
- **Net Metrekare**: Net square meters
- **Oda Sayısı**: Number of rooms
- **Bulunduğu Kat**: Floor level
- **Isıtma Tipi**: Type of heating system
- **Krediye Uygunluk**: Whether the property is suitable for a mortgage
- **Banyo Sayısı**: Number of bathrooms
- **WC Sayısı**: Number of toilets
- **Brüt Metrekare**: Gross square meters
- **Binanın Yaşı**: Age of the building
- **Binanın Kat Sayısı**: Number of floors in the building
- **Site İçerisinde**: Whether the property is inside a residential complex
- **Balkon Durumu**: Balcony availability
- **Eşya Durumu**: Furnishing status
- **Price**: Price of the property
- **Location**: The location of the property (city, district)

## Data Scraping
Web scraping was done using **Selenium**, a browser automation tool that allows interaction with dynamic web pages. Here's a brief overview of the scraping process:
- **Website**: [EmlakJet](https://www.emlakjet.com/)
- **Tool**: Selenium (with Chrome WebDriver)
- **Method**: Interaction with the EmlakJet website, navigating through multiple pages and extracting relevant data points.

The scripts for scraping the data are provided in the repository.

## Usage
To replicate the web scraping process or to use the provided scripts for your own purposes:
1. Clone the repository:
     git clone https://github.com/yourusername/house-price-scraping-emlakjet.git
2. Install the required libraries:
    pip install -r requirements.txt
3. Run the scraping script:
    python scraper.ipynp


Ensure that **Selenium** and **Chrome WebDriver** are correctly installed and configured on your machine.

## Requirements
- Python 3.x
- Selenium
- Chrome WebDriver
- Pandas
- BeautifulSoup (for HTML parsing)

## Kaggle Notebook
For a detailed walkthrough of the data scraping and subsequent analysis, you can refer to my [Kaggle notebook here](https://www.kaggle.com/code/gokhanergul/house-price-prediction-with-emlakjet-data-cleaning).

## Contact
For any inquiries or suggestions, feel free to reach out:
- **Email**: gokhannergull@gmail.com
