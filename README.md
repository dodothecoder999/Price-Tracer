# Amazon Price Tracker

A simple Python project that scrapes product information from Amazon using **Requests** and **BeautifulSoup**. It fetches the product title and current price from a given Amazon product URL.

## Features

- Fetch product title
- Fetch current product price
- Uses Requests for HTTP requests
- Uses BeautifulSoup for HTML parsing
- Easy to customize for different Amazon products

## Technologies Used

- Python 3
- Requests
- BeautifulSoup4
- lxml

## Project Structure

```
Amazon-Price-Tracker/
│── prictrac.py
│── requirements.txt
│── README.md
│── .gitignore
```

## Installation

### Clone the repository

```bash
git clone https://github.com/your-username/Amazon-Price-Tracker.git

cd Amazon-Price-Tracker
```

### Install dependencies

```bash
pip install requests beautifulsoup4 lxml
```

or

```bash
pip install -r requirements.txt
```

## Usage

Open `prictrac.py` and replace the product URL with your desired Amazon product.

Run the script:

```bash
python prictrac.py
```

### Example Output

```
HP Pavilion Plus Laptop
₹72,999
```

## How It Works

1. Sends an HTTP request to the Amazon product page.
2. Parses the HTML using BeautifulSoup.
3. Extracts:
   - Product Title
   - Product Price
4. Prints the extracted information to the console.

## Requirements

- Python 3.8+
- requests
- beautifulsoup4
- lxml

## Limitations

- Amazon frequently changes its website structure, so HTML selectors may need updates.
- Some product pages may block automated requests.
- Prices displayed may vary depending on location, availability, and account.

## Future Improvements

- Track multiple products
- Email notifications when prices drop
- Telegram or Discord alerts
- Save price history in a database
- Plot price trends over time
- Scheduled price monitoring

## Disclaimer

This project is intended for educational purposes only. Respect Amazon's Terms of Service and avoid sending excessive automated requests.

## Author

**Saniya Koyal**

GitHub: https://github.com/dodothecoder999
