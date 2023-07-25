# Automating racing data from lardbrokes and racenet websites for efficient and more accurate betting

## General Information
This Python script performs web scraping to extract horse racing data from two different websites and merges the information into a single DataFrame. The collected data includes race statistics, betting information, and other relevant details for each horse participating in a specific race.

It was a small part of one of my freelance projects, which I successfully developed a comprehensive automation solution for my client's punting process. This innovative system significantly streamlined the analysis phase, resulting in substantial time savings. By leveraging automation, we were able to achieve a more efficient and effective approach to punting, enabling my client to make informed decisions in a timely manner.

## Technologies Used
* Python: The programming language used for this project.
* Libraries:
    * selenium webdriver: It is used to create robust, browser-based regression automation suites and tests, scale and distribute scripts across many environments
    * pandas: Utilized to manipulate and structure the data into a DataFrame.
    

## Objectives
The main objectives of this real estate investment analysis were as follows:

* Data Collection: Gather detailed information on various horses, jockeys and trainers.
* Data Analysis: Utilize the collected data to perform a comprehensive analysis of each horses, jockeys and trainers, evaluating factors such as win rate, place rate, career success etc.
* Horse Ranking: Rank the horses based on their potential, considering the defined criteria, to identify the top-performing horses punting.

## Steps to use the script:

* Install the required libraries if you haven't already:
* Copy code
* pip install selenium pandas
* Download the appropriate ChromeDriver for your Chrome browser version and provide the file directory for path.
* Replace the website_racenet and website_ladbrokes variables with the links to the race pages you want to scrape data from.
* Execute the script in your preferred Python environment.

##Script Overview:

*The script uses the Selenium library to automate web browsing and data extraction.
*It starts by opening the Chrome web browser using the provided ChromeDriver path and navigates to the website_racenet.
*It scrapes various race details, including field conditions, horse names, and horse information like career stats, win rate, and more.
*After collecting the horse information from the first website, the script navigates to the website_ladbrokes.
*It then clicks on the "Bet Tracker" element to access the betting data for each horse.
*The script collects the horse names and corresponding betting data (pound_sign and dollar_sign).
*The data is merged into a single DataFrame (final_df), which includes all the information scraped from both websites.


## Permission:
Professional contract with the client has not been breached in this repository.


