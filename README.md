
## Installation
1. Install [ChromeDriver]:
   * Run `brew cask install chromedriver`
   * Confirm installation: `chromedriver --version`
   * Check location of ChromeDriver: `which chromedriver`
   * Wherever the `driver` is initialized in the code, insert the ChromeDriver location
2. Install Selenium: `pip install selenium`
3. Install BeautifulSoup: `pip install beautifulsoup4`

## Usage
#### To test `get_links.py`
1. Uncomment the last line `get_links.py`
2. Run `$ python get_links.py`

#### To run the entire script:
1. Set a number of pages you'd like to iterate through here
2. Run `$ python apply.py`
3. The script will open [glassdoor.com](https://www.glassdoor.com/index.htm), at which point you should log-in
4. From there on, everything is automatic!


