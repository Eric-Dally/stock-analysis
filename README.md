# VBA Green Stock Analysis

## Overview of Project
The purpose of this project was to analyze green stocks. Daily Market information was pulled from twelve companies from 2017 and 2018. Using VBA code, I was able to determine the total trade volume and yearly return for each stock. Not only that, but I was able to structure the code so that anyone can run it with a click of the button. 

## Results

Green stocks in 2017 did very well with 11 companies earning a positive return. On the other hand, stocks in 2018 underperformed with 10 companies earning a negative return. 

<img width="355" alt="2017 Results" src="https://user-images.githubusercontent.com/82424250/117390133-36ff1d80-aeb3-11eb-86e6-8db4f4f2fb79.png">

<img width="347" alt="2018 Results" src="https://user-images.githubusercontent.com/82424250/117390140-3bc3d180-aeb3-11eb-9a64-be0b613ffc45.png">

To improve the code, I refactored it using a three output array including the tickerIndex and tickerVolumes. As you can see, this significantly improved the run time by shaving off half a second.

**Initial Run times**:

<img width="258" alt="2017 Initial Run Time" src="https://user-images.githubusercontent.com/82424250/117390245-69a91600-aeb3-11eb-8298-8423de655b09.png">

<img width="254" alt="2018 Initial Run Time" src="https://user-images.githubusercontent.com/82424250/117390377-abd25780-aeb3-11eb-9d19-87e3ee7ef6a0.png">


**Refactored Code Run Times**:

<img width="255" alt="VBA_Challenge_2017" src="https://user-images.githubusercontent.com/82424250/117390405-b7258300-aeb3-11eb-8c8e-341af45f7f87.png">

<img width="254" alt="VBA_Challenge_2018" src="https://user-images.githubusercontent.com/82424250/117390442-d0c6ca80-aeb3-11eb-88cd-081a19fa6dbc.png">


## Summary

Refactoring the code allowed the computer to process information more quickly and efficiently. Orginally, the code processed all values from startingPrice to the endingPrice. However, the refactored code was able loop through the tickerIndex, tickerVolumes, and the rows simultaniously allowing it to perform quicker. 

Refactoring code is an benefitical because it reduces the processing speed. Although half a second may not seem important for 12 stocks, it makes a huge difference for 1000,000,000 stocks. By cutting down the run times, one can make more complicated projects run significantly more efficient. Furthermore, refactoring simplifies the design of the code making it easier to understand. This not only helps with debugging but also helps one consider new ways to build the code. 
