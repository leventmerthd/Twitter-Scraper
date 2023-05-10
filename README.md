# Twitter Scraper
This is a Python script that scrapes tweets from Twitter based on a specific search query using Selenium and BeautifulSoup libraries. The scraped tweets are stored in a Pandas dataframe for further analysis.

# Requirements
To run this script, you need to have the following:
* Python 3.x
* Selenium library (**pip install selenium**)
* BeautifulSoup library (**pip install beautifulsoup4**)
* ChromeDriver executable (can be downloaded from https://chromedriver.chromium.org/downloads)

# Usage
1. Clone this repository or download the script file (**twitter_scraper.py**) to your local machine.
2. Install the required libraries and ChromeDriver executable (if not already installed).
3. Open the script file and modify the following variables according to your needs:
```
twitter_user = "YOUR_USERNAME" # Twitter username
twitter_pass = "YOUR_PASSWORD" # Twitter password
search_query = "YOUR_KEYWORD" # Search query
tweet_count = 100 # Number of tweets to scrape
```
4. Run the script by typing the following command in your terminal:
```
python twitter_scraper.py
```
5. The script will start scraping tweets and will store them in a Pandas dataframe. Once the scraping is complete, the script will print the first five tweets on the console.

# Disclaimer
This script is for educational and research purposes only. Please make sure to follow the Twitter terms and conditions and respect other people's privacy and rights when scraping data from Twitter.
