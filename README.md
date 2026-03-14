# Market Basket Analysis for Product Bundling

This project performs Market Basket Analysis using the Apriori algorithm to identify relationships between products and recommend bundle items.

## Technologies Used
- React.js (Frontend)
- FastAPI (Backend)
- Python
- Apriori Algorithm
- Association Rule Mining

## Project Structure

```
market-basket-analysis
│
├── backend
│   ├── main.py
│   ├── groceries.csv
│   └── requirements.txt
│
├── frontend
│   ├── package.json
│   ├── public
│   │   ├── index.html
│   │   └── manifest.json
│   │
│   └── src
│       ├── App.js
│       ├── App.css
│       ├── index.js
│       └── components
│
└── README.md
```


## Features
- Product bundle recommendation
- Adjustable support, confidence, and lift
- Interactive dashboard
- Product relationship visualization

## Example Recommendation

If a customer buys:

whole milk

Recommended bundle products:
- yogurt
- rolls/buns
- sausage
- soda
