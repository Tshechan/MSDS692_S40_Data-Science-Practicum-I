# MSDS692_S40_Data-Science-Practicum-I

## Housing Price Prediction in the State of Colorado

## Regis University

### Table of contents 

**1. Project Description**

  A. Project Introduction
  
  	The real estate industry comprises of varieties of stakeholders ranging from regulatory bodies, private sectors and investing firms deeming it to be one of the vital sectors for revenue generation. These stakeholders have a high demand for better understanding of the real state’s growth mechanism and its return of investments (ROI). Colorado offers great opportunities for investment in housing market as recently it is observed that several real estate investors are interested to invest in this state. This project can be considered as an evidence-backed step towards a rational decision making for the benefit of those investors. This project focused on predicting the most favorable cities in Colorado to invest in and get highest return of investment (ROI) based on data from Zillow. In addition to this, we have performed exploratory data analysis (EDA) on data collected from Redfin to analyze impacting features and find out their correlation to housing prices. This project provides a recommendation on which five Colorado State metro areas are the most prime for investing in now and selling a year from now.




  B. Problem Statement
  
 The goal of this research project is to explore the model to predict, with time series analysis, which cities in Colorado state are best for real estate investment. This analysis will appeal investors as it will help them make choices by predicting the estimated return of investment (ROI) for their investment in certain cities in the state of Colorado. This study finds out which 5 cities may yield high ROI percentage if invested.


**2. Data Collection**

For this project,the datasets used are Zillow research data and Redfin housing market data available from zillow and Redfin websites.

**3. Generic Flow Of Project**

A. Data processing

B. Data Exploration and Visualizations

C. Model Approach and development

D. Model Validation and comparision

E. Predictions

**4. EDA**

      
We are focusing in Colorado state so filtered out data for Colorado only. Then, we check if there are any missig values and worked on those missing values.
  

**5. Model Approach**

For the analysis, we have done simple EDA based approach to find the top five cities with ROI percentage as well as used time series ARIMA model for predicting the ROI percentage and the top five cities. Whereas, performed EDA for exploring the other factors relationship during the same time period of time.  


**6. Conclusion**

<img width="1013" alt="Screen Shot 2022-10-16 at 5 11 25 PM" src="https://user-images.githubusercontent.com/109038700/196077873-c0c83fb8-86af-4cd7-b046-bb19d2ad3127.png">

<img width="969" alt="Screen Shot 2022-10-16 at 5 13 00 PM" src="https://user-images.githubusercontent.com/109038700/196077947-c272e593-0792-4ffd-8e7c-b46ca6465039.png">

<img width="975" alt="Screen Shot 2022-10-16 at 5 12 24 PM" src="https://user-images.githubusercontent.com/109038700/196077965-95f44bcd-e129-4f71-aa94-88fd4ef7d98b.png">

<img width="955" alt="Screen Shot 2022-10-16 at 5 46 34 PM" src="https://user-images.githubusercontent.com/109038700/196078090-3a3f9b69-2167-4d47-ac8e-5f281b01d4b3.png">

<img width="978" alt="Screen Shot 2022-10-16 at 5 13 45 PM" src="https://user-images.githubusercontent.com/109038700/196078121-c73af338-1626-4739-bc90-988d8f7812f3.png">


In our analysis, we can see that ARIMA models trained on data from 2012 - 2020 and tested on data from 2020- 2021 fairly outperformed an EDA based approach on the same time periods which shows that applying modeling was worth our effort. During simple EDA based analysis for selecting which five cities to invest in resulted in an ROI of 36.49% where the ARIMA model-based approach resulted in an ROI of 38.51%. Furthermore, it should be taken into consideration that the ARIMA based analysis had an error of 19.06% i.e., the predicated value deviated. 19.06% from the actual values for the test period. Apart from this, for the comparison of the model’s prediction we have also performed Facebook prophet model prediction which gave us top five cities which included the same three cities from our ARIMA model showing us that the model performed well. The graphs shown above provides us the predictions of top five cities with highest predicted ROI.


**7. Limitation and Future Considerations**

There are other factors that I would also like to study about these metro areas to better understand whether median home price can really keep growing as predicted. For instance, the information about wage growth in Colorado, migration data as well as inflation data to determine whether prices in the Colorado metro areas are already close to the maximum the market will allow. Also, the ROI percentage obtained seems high in some metro areas, it would be better to do more research to figure out the sustainability of the rapid growth of house prices seen in recent years. Further analysis may include building linear model with additional features such as federal income tax rate and housing market safety score and more.![image](https://user-images.githubusercontent.com/109038700/196077657-5970b7f0-80b8-480e-b7ae-b5e9a6c56819.png)


**Data sources:**

https://www.zillow.com/research/data/ 

https://www.redfin.com/news/data-center/ 
