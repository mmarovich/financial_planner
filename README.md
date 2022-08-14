# Financial Planner

This is a financial planner that takes the client's current crypto / stock portfolio, and calculates whether they've reached their emergency fund goals, as well as their retirement goals.  The app pulls in data from the Alpaca API to evaluate data from the last 3 years, and simulate what the next 10 / 30 years looks like using Monte Carlo.

---

## Technologies

Dependencies:

* pandas
* os
* requests
* json
* dotenv
* tradeapi
* MCForcastTools (Local File)
* datetime

Tech & Languages:

* Python
* Anaconda
* Jupyter lab

---

## Installation Guide

From the terminal:

```
git clone git@github.com:mmarovich/financial_planner.git
cd financial_planner
pip install pandas os requests json dotenv tradeapi datetime
conda activate <dev name>
Jupyter lab
```

---

## Contributors

This is the module 5 challenge from 2U's FinTech bootcamp

---

## License

MIT
