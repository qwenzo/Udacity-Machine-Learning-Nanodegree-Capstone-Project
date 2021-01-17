# Starbucks Capstone Challenge
Udacity Machine learning Nanodegree

### Table of Contents

1. [Installation](#installation)
2. [Files](#files)
3. [Acknowledgements](#licensing)

## Installation <a name="installation"></a>

This project requires a python envirnoment (+v3.) along with the libraries seaborn, sklearn, pandas, maatlibplot and numpy.


## Files <a name="files"></a>

The data used in this project is a simplified data from the Starbucks Reward App.

The data is contained in three files:
- `portfolio.json` - containing offer ids and meta data about each offer (10 rows x 6 columns)
- `profile.json` - demographic data for each customer (17000 rows x 5 columns)
- `transcript.json` - records for transactions, offers received, offers viewed, and offers completed (306534 rows × 4 columns)

data description:

`portfolio.json`
- id (string) - offer id
- offer\_type (string) - type of offer ie BOGO, discount, informational
- difficulty (int) - minimum required spend to complete an offer 
- reward (int) - reward given for completing an offer
- duration (int) - time for offer to be open, in days
- channels (list of strings)

`profile.json`
- age (int) - age of the customer
- became\_member\_on (int) - date when customer created an app account
- gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
- id (str) - customer id
- income (float) - customer's income

`transcript.json`
- event (str) - record description (ie transaction, offer received, offer viewed, etc.)
- person (str) - customer id
- time (int) - time in hours since start of test. The data begins at time t=0
- value - (dict of strings) - either an offer id or transaction amount depending on the record


## Acknowledgements<a name="licensing"></a>

Credits to Starbucks for providng the dta for this Nanodegree.

