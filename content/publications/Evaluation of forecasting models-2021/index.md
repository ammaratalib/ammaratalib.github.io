---
abstract: Evapotranspiration (ET) prediction and forecasting play a vital role in improving water use in agriculturally intensive areas. Metrological and biophysical predictors that drive ET in managed landscapes have complex nonlinear relationships. Deep learning and data-driven methods have shown promising performance for identifying the dependencies among variables. Here, we evaluated the potentials of random forest (RF) and long short-term memory (LSTM) neural networks to estimate and forecast daily ET for corn, soybeans, and potatoes in diverse agricultural farms during 2003–2019. The modeling framework was applied for nineteen fields where eddy covariance ET and meteorological observations in the Midwest USA for growing season (April-October) is available. In this study, we applied data-driven models (RF and LSTM) with 3 sets of predictors (5, 11, and 16 predictors). Results show that a 16 predictor RF model (RF_16 R2 = 0.7, Willmott’s skill score = 0.90) outperformed a process-based land surface model (LSM R2 = 0.57, Willmott’s skill score = 0.86) for predicting daily ET, while LSTM performance was lower (LSTM_16 R2 = 0.65, Willmott’s skill score = 0.89 and LSTM_11 R2 = 0.62, Willmott’s skill score = 0.86) than RF using the same sets of predictors. Vapor pressure and crop coefficients were identified as the most important predictors for irrigated crops, while short wave radiation and enhanced vegetation index were key predictors for non-irrigated crops. For certain crop types, such as corn and soybeans on fine-grained soils (silt loam), a simpler version RF, using only 11 drivers, can provide comparable results (R2 = 0.70 vs 0.69 and Willmott’s skill score = 0.90 vs 0.88). For short-term 3-day ET forecasting, LSTM is more sensitive to uncertainty in ensemble forecast meteorology than RF. ET forecasts were strongly sensitive to forecast uncertainty of vapor pressure. The proposed modeling architecture provides a field-scale, locally calibrated tool for accurate prediction and short-term forecasting of daily ET in areas where in situ ET, metrological, and biophysical data are lacking.
authors:
- admin
#- '**Ammara Talib**'
- Ankur R.Desai
- Jingyi Huang
- Tim J.Griffis
- David E.Reed
date: "2021-06-14T00:00:00Z"
doi: "https://doi.org/10.1016/j.jhydrol.2021.126579"
featured: false
image:
  caption: #'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'#
  focal_point: ""
  preview_only: false
projects: [INCOMPASS]
publication: '*Journal of Hydrology* 600: 126579'
publication_short: ""
publication_types:
- "2"
publishDate: "2021-09-01"
#slides: "Measuring EC Fluxes"
summary: Random Forest (RF) and recurrent neural network models such as LSTM predict field-scale ET more accurately than process-based models. Vapor pressure and crop coefficients are key predictors for irrigated crops. ET forecasting for non-irrigated crop requires enhanced vegetation index. Short-term (3-day) forecasts have lower uncertainty, higher accuracy using RF.  
tags:
- Evapotranspiration
- Machine learning
- Agriculture
- Drought
- Irrigation
- Forecasting
- Neural Networks
title: Evaluation of prediction and forecasting models for evapotranspiration of agricultural lands in the Midwest US
url_code: ""
url_dataset: ""
url_pdf: "https://reader.elsevier.com/reader/sd/pii/S0022169421006260?token=B4AFDDB826E11BCF979ADF2CA0409137E0E763A38B4D0A4412503D185AEDA1A9FEBDAE2E5C247CF8536B91EA3B3B2CC4&originRegion=us-east-1&originCreation=20221129005538"
url_poster: ""
url_project: ""
#url_slides: "https://drive.google.com/file/d/1EBhFqQHLVsmkfEHQ-yfFA2xZRrGaih_c/view?usp=sharing"
url_source: ""
url_video: ""
---
