StockTradeApp
A basic stock trading simulation app created using IEX's stock API, Python, SQL, and Flask. Fun project, demo link: https://stocktradeapp.onrender.com *May not work since IEX API data is on a paid tier. Currently using free trial.

# Run app locally

First run:

```
pip install -r requirements.txt
```

Next, create an account on IEX Cloud and get an API key. Then add this API key to your system:
```
export API_KEY=YOURKEY
```

Lastly, run
```
flask run
```
