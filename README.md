# Green Stock Analysis

## I. OVERVIEW OF PROJECT

### 1.Background
Steve loved the workbook that we initially created for him. Although our code works well for a dozen stocks which has been helpful for him in his research for his parents,
He is looking to expand the dataset to include the entire stock market over the last few years.

### 2. Purpose
My task is therefor to refactor my previous code in order to loop through all the data one time in order to collect the same information  used before. I will also have the mission
to mesure the performance (time elapsed) of the code and compare it to my initial code.

## II. Results
As elaborate previously the purpose of refactoring our code is to see if it's more efficient. In order to complete this task , I had to create 3 new arrays.
tickerVolumes,tickerStartingPrices,tickerEndingPrices.
The above 3 arrays store performance data for each stock when the for loop analyzes it. 
The ticker array I created in the original code creates a ticker that can be called for each stock, then Compare the 3 performance arrays to the ticker array using a variable named tickerIndex. 
Once these arrays are created, I can use nested for loops and variables to iterate through the data and complete the analysis.

**1. Original code vs Refactored code

**Original code

https://github.com/Simro25011/stock-analysis./blob/main/Original%20Code.txt

**Refactored code

https://github.com/Simro25011/stock-analysis./blob/main/Refactored%20Code.txt

Let's compare then the stock performance between 2017 and 2018

The performance of green stocks in 2017 has changed a lot compared to 2018. Only 2 of the 12 stocks ENPH and RUN generated positive ROI in both years. 
Trading volumes for many stocks are also falling.

https://github.com/Simro25011/stock-analysis./blob/main/Ressources/Stock%20Performance%202017.png

https://github.com/Simro25011/stock-analysis./blob/main/Ressources/Stock%20Performance%202018.png

**2.Execution time

Improving code efficiency is a success! The execution time improved from 0.5234375 seconds to 0.0703125 seconds in 2017 and from 0.5390625 to 0.0625 in 2018.
We are saving a lot of time.

***Execution time for 2017 Original Coding*** 

 https://github.com/Simro25011/stock-analysis./blob/main/Ressources/Execution%20Time%20for%20Original%202017%20coding.png

***Execution time for 2017 Refactored Coding***
 
https://github.com/Simro25011/stock-analysis./blob/main/Ressources/VBA_Challenge_2017.png

***Execution time for 2018 Original coding*** 

https://github.com/Simro25011/stock-analysis./blob/main/Ressources/Execution%20Time%20for%20Original%202018%20coding.png

***Execution time for 2018 Refactored Coding***

https://github.com/Simro25011/stock-analysis./blob/main/Ressources/VBA_Challenge_2018.png

## Summary

### 1. Advantages of refactoring a code

One thing for sure We are saving a lot of time. over 45 secs actually and this can definelty be significative when we run thousands of data.
the goal is by taking fewer steps, using less memory, or improving the logic of the code to make it easier for future users to read.


### 2. Inconvenients of refactoring a code
When it comes to refactoring the main source of concern is to avoid make errors
