https://www.kaggle.com/c/competitive-data-science-predict-future-sales

## Overview

In this competition you will work with a challenging time-series dataset consisting of daily sales data, kindly provided by one of the largest Russian software firms - 1C Company. 

We are asking you to predict total sales for every product and store in the next month. By solving this competition you will be able to apply and enhance your data science skills.

## Evaluation

Submissions are evaluated by root mean squared error (RMSE). True target values are clipped into [0,20] range.

Submission File

For each id in the test set, you must predict a total number of sales. The file should contain a header and have the following format:

ID,item_cnt_month
0,0.5
1,0.5
2,0.5
3,0.5
etc.
