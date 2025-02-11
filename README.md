Steps to run the script

1) Open the .ipnyb file in the databricks notebook

<img width="1470" alt="image" src="https://github.com/user-attachments/assets/27145094-b466-4785-9383-2ebf72147244" />


2) Define the .csv and .parquet file' path in 3rd cell of notebook (need to upload them in dbfs first)

<img width="1470" alt="image" src="https://github.com/user-attachments/assets/c0ccfb39-a6d0-4f9c-bc2e-7e3ff7137190" />


3) Install all the libraries by running the first cell

4) Then click on Run All in top right corner (will take less than 30 minutes to run all code)

==> Data Collection: For UniSwap v2, UniSwap v3, and Cowswap, write a program that downloads and saves all swaps for a       
    specific market within a specific month into a database (to ensure manageable data size).

    Cell 8, 9, and 10 will give a link to download each swap dataset
![alt text](image.png)

<img width="1470" alt="image" src="https://github.com/user-attachments/assets/b357c86f-8552-4762-b7ae-23c7a14d6b1f" />


==> Price Analysis: For each trade, compare the realized swap price to the mid-price on Binance.

    Cell 13, 14, and 16 will give an analysis of price difference as new columns and also created graph

![Price_Difference_Plot](https://github.com/user-attachments/assets/cb12e9a0-31d4-41c5-8836-3290594c80e5)
ce_Differerence_Scatter](https://github.com/user-attachments/assets/e1d9bf68-00c0-4b28-9990-e958d981e1e1)



==> Visualization: For each exchange, create a graph with trade size in USD on the horizontal axis and average cost on the vertical axis.

    Cell 23 has various graphs for each trade
![UniSwap2_Bars](https://github.com/user-attachments/assets/f674e0fc-bb4c-4e7c-a5bf-375b3066ba50)
![CoSwap_bars](https://github.com/user-attachments/assets/25b8d765-10c3-488a-838d-e6568b12ba78)

Note: Please each cell in sequence to achieve desired result
    

