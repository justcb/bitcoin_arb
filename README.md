# bitcoin_arb
This analysis compares bitcoin prices on two different crypto exchanges and looks for price differences, seeking arbitrage opportunities.  There are very rare instances where the price of a crypto asset differs from one exchange to another.  However, in those instances, risk-free money is there for the analyst fast enough to identify it and execute on the information.  This bitcoin arbitration application assists in locating just such opportunities between two different exchanges.  Here, we are looking at bitstamp and coinbase.

---

## Technologies

This bitcoin arbitration application runs in a Jupyter Notebook.  

It imports pandas, Path from pathlib, and matplotlib.

---

## Installation Guide

No istallation is required, other than loading in Jupyter Notebook.  To do so, navigate to the directory containing the notebook in terminal or GitBash.  There, type `jupyter lab`

---

## Usage

Bitcoin Arbitrage comes packaged with a test set of data from January to March 2018 for the Bitstamp and Coinbase exchanges.

After importing the data, Bitcoin Arbitration cleans the data by removing null values, removing non-numerical characters, normalizing the column types, and removing duplicates.  See screenshots below.


After the data is cleaned, Bitcoin Arbitrage identifies and presents with a plot overlay, the potential arbitrage opportunites for early, middle, and late dates in the time period.


Finally, it computes the profits possible for the arbitrage opportunities.

---

## Contributors

This project was created as a part of the Rice FinTech Bootcamp.

---

## License

This software is licensed for use under the included MIT License.