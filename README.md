# OutbreakPAD.1.1
Healthcare-associated infection outbreaks (HAIOs), a sudden increase in the incidence of a disease in a healthcare setting, is usually caused by bacterial or fungal pathogens and  results in substantial morbidity and mortality and increase healthcare costs. Outbreak Predictor and Detector (OutbreakPAD) is a Python 3 library that aims to capture the unusual signal of incidence rise and therefore assist in the early recognition of HAIOs. The online service version of OutbreakPAD is freely available at https://github.com/pandafengye/OutbreakPAD
## Algorithm:
The daily (or weekly) case number in a hospital (or a ward, an inpatient building) constitute a time series data set, based on which prediction and detection of HAIOs are carried out. 
  # Prediction: a combined model of autoregressive integrated moving average (ARIMA) and generalized regression neural network (GRNN).
  # Detection: seven algorithms, including Mann-Kendall, Pettitt, Buishand U Test and Standard Normal Homogeneity Test (SNHT), CUSUM, EWMA and P value-CUSUM.
In theory, OutbreakPAD can also applies to other outbreaks based on time series data.
# Download and install
```bash
git clone https://github.com/pandafengye/OutbreakPAD.1.1.git    
cd OutbreakPAD.1.1  
python setup.py install 
```
