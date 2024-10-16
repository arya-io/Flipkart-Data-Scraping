# Flipkart-Scraping

## Overview
This project is a web scraping application that extracts product details from Flipkart's mobile section. The scraper gathers information on various products, including their names, prices, descriptions, and ratings, across multiple pages. It is designed to help users understand how to collect and organize data from e-commerce websites for analysis.

## Features
- Scrapes product names, prices, descriptions, and ratings.
- Navigates through multiple pages of product listings.
- Utilizes Selenium for dynamic content handling and BeautifulSoup for data extraction.
- Saves the collected data into a CSV file for further analysis.

## Technologies Used
- Python
- Selenium
- BeautifulSoup
- Pandas

## Installation
To run this project, you'll need to have Python installed on your machine. Follow these steps to set up the environment:

1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Flipkart_Scraping.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Flipkart_Scraping
   ```

3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open the Jupyter Notebook file `Flipkart_Scraping.ipynb`.
2. Run each cell step-by-step to execute the web scraping process.
3. The scraped data will be saved in `Flipkart_Scraping.csv` in the project directory.

## Note
Please ensure you comply with Flipkart's terms of service when scraping their website.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any enhancements or suggestions.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- [Selenium Documentation](https://www.selenium.dev/documentation/)
- [BeautifulSoup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
