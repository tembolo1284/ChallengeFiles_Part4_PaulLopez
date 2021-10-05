# Project Title

This is the Risk Return Analysis Application for challenge 4! I pull in one CSV file with prices from four funds and the S&P 500.
I do a daily return analysis and comparison and plot a chart to see the four funds and the S&P 500. I then create box plots
with and without the S&P 500 to compare the volatility of the S&P 500 to the funds, and to compare the funds with themselves.

I then analyze the risk of the funds and S&P 500 by running analysis of the standard deviations. I then annualize and analyze further.
I conclude by doing a rolling 21 day std deviation calculation and I plot all the funds together with the S&P 500, and the 4 funds just by themselves.

THe next step in the analysis is calculating the sharpe ratios and plotting them in a box chart. It quickly becomes clear 
which fund has the best and worst risk-return profile

---

## Technologies

I am using python version 3.7.10 and am importing the following from the built-in libraries and from functions i've created myself:
import pandas as pd
from pathlib import Path
%matplotlib inline

---

## Installation Guide

I have python version 3.7.10 and git version 2.33.0.windows.2 installed on a laptop running windows 10 pro.

I launch jupyter lab from the gitbash terminal and then run the risk_return_analysis noteback from the 
webpage that launches.


---

## Usage

I have one csv file in the Resources folder named whale_navs.csv.  All that needs to be
done by the user is hit the double arrow and run the code. 

That's it!


---

## Contributors
Just me, Paul Lopez.


---

## License
No licenses required. Just install everything for free, pull from my repository, and enjoy!
