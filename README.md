# VBA Green Stock Analysis

## Overview of Project
The purpose of this project was to analyze green stocks. Daily Market information was pulled from twelve companies from 2017 and 2018. Using VBA code, I determined the total trade volume and yearly return for each stock. Not only that, but I was able to structure the code so that anyone can run it with the click of a button. 

## Results

Green stocks in 2017 performed very well with 11 companies earning a positive return. On the other hand, stocks in 2018 underperformed with 10 companies earning a negative return. 

<img width="355" alt="2017 Results" src="https://user-images.githubusercontent.com/82424250/117390133-36ff1d80-aeb3-11eb-86e6-8db4f4f2fb79.png">

<img width="347" alt="2018 Results" src="https://user-images.githubusercontent.com/82424250/117390140-3bc3d180-aeb3-11eb-9a64-be0b613ffc45.png">


To improve the code, I refactored it by creating three output arrays including the tickerIndex and tickerVolumes. As you can see, this significantly improved the run time by cutting off half a second from the intial run times.

<img width="446" alt="Screen Shot 2021-05-06 at 11 47 07 PM" src="https://user-images.githubusercontent.com/82424250/117399204-a1b95480-aec5-11eb-8370-b75ad6952dad.png">


**Initial Run times**:

<img width="258" alt="2017 Initial Run Time" src="https://user-images.githubusercontent.com/82424250/117399431-286e3180-aec6-11eb-97ea-4c294310b8ca.png">
                                                  
<img width="254" alt="2018 Initial Run Time" src="https://user-images.githubusercontent.com/82424250/117390377-abd25780-aeb3-11eb-9d19-87e3ee7ef6a0.png">


**Refactored Run Times**:

<img width="255" alt="VBA_Challenge_2017" src="https://user-images.githubusercontent.com/82424250/117390405-b7258300-aeb3-11eb-8c8e-341af45f7f87.png">

<img width="254" alt="VBA_Challenge_2018" src="https://user-images.githubusercontent.com/82424250/117390442-d0c6ca80-aeb3-11eb-88cd-081a19fa6dbc.png">


## Summary

Refactoring this code allowed the computer to process information more quickly and efficiently. Originally, the code processed all values from the startingPrice to the endingPrice. However, the refactored code was able to loop through the tickerIndex, the tickerVolumes, and the rows simultaniously allowing it to perform quicker. 

In general, refactoring code is benefitical because it reduces the computers processing time. Although half a second may not seem important for 12 stocks, it makes could make huge difference for 1000,000,000 stocks. By cutting down the run times, one can most likley imrove the run time of more complicated projects. In addition, refactoring simplifies the design of the code making it easier to understand. This not only helps with debugging but also helps one consider new ways to build the code. 
