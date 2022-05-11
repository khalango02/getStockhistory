# getStockhistory

Start server: python main.py

Usage:

POST: /getHistory

Body:
{
    "stock":"AAPL",
    "country": "United States",
    "from_date": "01/01/2010",
    "to_date": "01/01/2020"
}

return 200: JSON
