# Project Title

This is the Crypto Arbitrage Analyzer Application for challenge 3! I pull in two CSV files with prices from two 
different exchanges. I spend the first part of the code cleaning the data and removing blanks and NAs from each file. I also remove the
dollar sign from the close column from both csv files so I can then do some arithmetic calculations on them in the second
part of the analysis.

---

## Technologies

I am using python version 3.7.10 and am importing the following from the built-in libraries and from functions i've created myself:
import pandas as pd
from pathlib import Path
%matplotlib inline

---

## Installation Guide

I have python version 3.7.10 and git version 2.33.0.windows.2 installed on a laptop running windows 10 pro.

I launch jupyter lab from the gitbash terminal and then run the crypto_arbitrage noteback from the 
webpage that launches.


---

## Usage

I have two csv files in the Resources folder.  They are bitstamp.csv and coinbase.csv.  All that needs to be
done by the user is hit the double arrow and run the code. If they want to select different dates or timeframes, they
will be able to change that.  They can also filter the profitable trade tolerance which is currently set to 1%

The user is also free to change the scaling of any of the plots that are used throughout the code if they feel
they want a slightly different picture of things.

That's it!


---

## Contributors
Just me, Paul Lopez.


---

## License
No licenses required. Just install everything for free, pull from my repository, and enjoy!
