Steps to run the script

1) Open the .ipnyb file in the databricks notebook

2) Define the .csv and .parquet file' path in 2nd cell of notebook (need to upload them in dbfs first)

3) Install all the libraries by running the first cell

4) Then click on Run all in top right corner (will take less than 30 minutes to run all code)



==> Data Collection: For UniSwap v2, UniSwap v3, and Cowswap, write a program that downloads and saves all swaps for a       
    specific market within a specific month into a database (to ensure manageable data size).

    Cell 8, 9, 10 will give a link to download each swap dataset
    ![alt text](image.png)

==> Price Analysis: For each trade, compare the realized swap price to the mid-price on Binance.

    Cell 13, 14, 16 will give an analysis of price difference as new columns and also created graph

==>Visualization: For each exchange, create a graph with trade size in USD on the horizontal axis and average cost on the vertical axis.

    Cell 23 have various graphs for the each trade

Note: Please each cell in sequence to achieve desired result
    

