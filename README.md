# Challenge_3
Challenge 3 - Columbia Fintech


## Technologies
Used Jupyter Lab Extension for VS code (Python 3.8)
Imports: Pandas (for dataframes)
         Pathlib from path (used to generate file path to read csv data file)
         matplotlib inline (used to generate plots)

## Usage
The script reads in bitcoin price data from 01/218 to 03/2018 from 2 different exchanges: Coinbase and Bitstamp.  The data is cleaned and analyzed to find any potential arbritrage between the 2 exchanges.  I select certain dates that would appear to be profitable and analyze them further.  I then calculate the arbritrage spreads for each day and filter which trades are profitable, and can also cover the 1% transaction cost.  Last, I calculate the profit per trade and find the cumulative some of all profitable trades for the day.

## Contributors
Eric Conklin