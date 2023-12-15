# Metabolic-Syndrome-Forecast
The National Institutes of Health guidelines define metabolic syndrome as "a group of conditions that together raise your risk of coronary heart disease, diabetes, stroke, and other serious health problems.

The dataset for analysis came from the NHANES initiative where the following variables were combined from multiple tables with SQL, aquired from <a href="https://data.world/informatics-edu/metabolic-syndrome-prediction">Data World</a>.

<img width="800" alt="image" src="https://github.com/dimLMT/Metabolic-Syndrome-Forecast/assets/36935946/ac3e1538-feeb-45d9-aa35-08405ca92ed2">




<img width="660" alt="image" src="https://github.com/dimLMT/Metabolic-Syndrome-Forecast/assets/36935946/ba92a022-c682-4def-ab09-9b49880515b1">

#### We tried various feature engineering approaches and employed neural networks to build a predictive model.
With machine learning, the best result comes from the bagging decision tree model.

<img width="417" alt="image" src="https://github.com/dimLMT/Metabolic-Syndrome-Forecast/assets/36935946/ef3c03e0-b7ae-457f-a553-8ff14ca4fea0">

With deep learning, the best result leads to these metrics.

<img width="399" alt="image" src="https://github.com/dimLMT/Metabolic-Syndrome-Forecast/assets/36935946/bb376330-c1af-46fa-8282-4c17d4c54f79">

These results are acceptable but require further improvement, especially for medical datasets where avoiding False Negatives is crucial.
