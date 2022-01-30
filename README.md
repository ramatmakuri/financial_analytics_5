# Financial Analytics - Montecarlo simulation 
____


The program evaluates four new investment options for inclusion in the client portfolios. The program determines the fund with the most investment potential based on key risk-management metrics: the daily returns, standard deviations, Sharpe ratios, and betas.

## Packages Used
This project leverages python 3.7

## Installation Guide
The application requires the below programs to be installed

* python
* pandas 
* pathjlib 
* matplotlib 
* requests
* json
* dotenv
* alpaca_trade_api
* MCForecastTools


## Project functionality and Examples of Usage:
The project fetches the crptocurrency and stock data from alternative.me and alpaca respectively, using unauthenticated and authgenticated API calls

The program consist of 2 parts:

1. Analyze the adequqcy of emergency funds (promarily stored in cyrptoi currency)
<img width="1016" alt="Screen Shot 2022-01-29 at 10 42 00 PM" src="https://user-images.githubusercontent.com/96159292/151689683-70eea4f6-cbe0-4a8c-b837-14c74c240e48.png">
<img width="1079" alt="Screen Shot 2022-01-29 at 10 42 23 PM" src="https://user-images.githubusercontent.com/96159292/151689685-c4513a64-d50d-415d-b317-55aed9f5903b.png">
<img width="1096" alt="Screen Shot 2022-01-29 at 10 43 14 PM" src="https://user-images.githubusercontent.com/96159292/151689686-12427995-01a3-4950-ba9f-6969236441ac.png">

2. Analyze the expected return on retiremennt portfolio made of stocks and bonds using Monte Carlo simulation. Also, comparisions are made between alternate investment scenarios using different portfolio weights, in order to determine the possible invesetment mix that will enable early retirement or higher growth in the  investment value.
<img width="1097" alt="Screen Shot 2022-01-29 at 10 43 33 PM" src="https://user-images.githubusercontent.com/96159292/151689705-818cc288-3ae4-4f6c-948f-842b8aa52783.png">
<img width="8" alt="Screen Shot 2022-01-29 at 10 44 02 PM" src="https://user-images.githubusercontent.com/96159292/151689707-91035ef7-c8c2-4173-94a7-ba241dc9047f.png">
<img width="1107" alt="Screen Shot 2022-01-29 at 10 44 11 PM" src="https://user-images.githubusercontent.com/96159292/151689708-64beef21-f487-4553-99bf-1cf97ee922f9.png">
<img width="1101" alt="Screen Shot 2022-01-29 at 10 44 25 PM" src="https://user-images.githubusercontent.com/96159292/151689709-e075c298-fc7a-4241-b1fd-1182271fb91d.png">


## Contributors
Brought to you by Ram Atmakuri (ram.atmakuri@outlook.com) 

## License [MIT] (https://choosealicense.com/licenses/mit/)
