# trend-following-ma-long-short

Simple trend following strategy.

Uses two moving averages, 42 and 252 days.

## Long
Given 42 days moving average  
When + *SD* points above 252 days moving average  
Then be long

## Short
Given 42 days moving average  
When - *SD* points below 252 days moving average  
Then be short  

## Stay in cash
Given 24 days moving average  
When within a range of +/- *SD* points around 252 days moving average  
Then stay in cash  
