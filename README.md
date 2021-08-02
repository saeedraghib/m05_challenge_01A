# *Crypto Arbitrage - (m03_challenge_01):*<br><br>

## **Description:**<br>
This project is designed to consider Arbitrage opportunities in Bitcoin and other cryptocurriencies (to be introduced later). As Bitcoin trades on markets across the globe, we want to capitalize on simultaneous price dislocations in those markets by using the powers of Pandas.

For this assignment, we will sort through historical trade data for Bitcoin on two exchanges: Bitstamp and Coinbase. The task is to apply the three phases of financial analysis to determine if any arbitrage opportunities exist for Bitcoin.

<br>

## **Phase 1: Collect the Data**<br>
The two files "bitstamp.csv" and "coinbase.csv" were read in to two separate datframes. The files were then tested to make sure that "read" of the file was successful.
<br>

## **Phase 2: Prepare the Data**<br>
The two dataframes "bitstamp" & "coinbase", containing the file data were then further cleaned and prepared for analysis as follows:
1. *Null Values* were removed, since they were not more than 0.13%.
2. *'$'* was removed from the column labeled 'Close'.
    *   *used an 'if' clause to check column type before using a a 'string' function*
        * *This eliminates the error that might arise if a 'string function' is called on a data-type that is not string*
3. *type* of the column (which was 'object' / string), was changed to float.
    *   *used an 'if' clause to check column type before changing the type to 'float'*
        * *This eliminates the error that might arise if you try to change the type of data column that is already the correct type.*
<br>

## **Phase 3: Analyze the Data**<br>
Phase 3 completed to step4.6
<br>

---

## Technologies

The following packages and dependicies are needed for the proper functioning of the application:
### *pandas:*  
pandas is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool,
built on top of the Python programming language.
<br>
### *pathlib:*
The Pathlib module in Python simplifies the way in working with files and folders. The Pathlib module is available from Python 3.4 and higher versions. It combines the best of Python's file system modules namely os, os.path, glob, etc.
<br>
### *matplotlib:*
Matplotlib is a plotting library for the Python programming language and its numerical mathematics extension NumPy. It provides an object-oriented API for embedding plots into applications.
<br>

---

## Usage

In order to run the program, type the following at the terminal prompt:
* ### python sr_crypto_arbitrage.ipynb

---

## Contributors

**Name:** Saeed A Raghib<br>
**Contact:** saeed_raghib@msn.com

---

## License

### Universit of California at Berkeley EXTENSION
