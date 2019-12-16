# SocialMediaDataMiningProject

# Introduction

Every year, diseases like Flu, Dengue causes millions of death all around the world. We are taking use cases to predict the outbreak of the diseases, nowcast, and forecast so as to determine trends on how they spread around the world. Initially, our data set was on the Flu, but we came across a competition on trend prediction, hosted by drivendata.org - DengAI Competition

The dataset that is provided is having details of climate, vegetation along with the number of Dengue cases that can be found in the National Oceanic and Atmospheric Administration. We thought it would be interesting to predict the trends and simultaneously correlate the outbreak with Google trends.

# Motivation

During our research, we came across the competition hosted by drivendata.org which was to predict the Dengue trends in cities of San Juan and Iquitos based on the dataset provided by datadriven.org. There was huge widespread Dengue all over the world and we wanted to explore more on how it spreads and determine the influence of climate and other factors on the Dengue outbreak. Based on the research that was conducted in Singapore, it seemed that taking factors like weather into consideration might actually bring some new insights into the dengue prediction and it may vary according to locality and it is also specific to climatic conditions for the mosquito to breed as well. 

It was terrifying to see the outbreak of Dengue in Africa, India and we decided to go with the dataset given by the competition to predict the trends of Flu in cities of San Juan and Iquitos. We observed that the data set is raw and it needed preprocessing and data division into cities for easier processing of the data. We will be using two techniques - ARIMA and SARIMA and compare both  models.

# Methodology

We did explore many methods to predict dengue. Initially, we planned to forecast the predictions using ARIMA. We used it to predict the number of dengue cases and compared them with the actual values. We started with a basic and simple ARIMA and used only the total cases for the prediction. We found that the MSE value was high. Upon going through multiple research papers about dengue predictions using ARIMA, we came across multiple papers where they used ARIMA and SARIMA models to compare the data. Also, we found that dengue was a seasonal disease so we planned to go ahead with SARIMA as well.

We read a paper about Dengue prediction using SARIMA where it was explained how it gives accurate results when compared to ARIMA because it is least affected by false alarms. We then figured out there is an extension of ARIMA, SARIMA which takes consideration of the season factor that dengue depends on. Details of the MSE, predictions, and observations are described in detail in the next section.
