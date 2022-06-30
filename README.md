# prediction-missing-values

missing values, an imbalance of the labels, or heavy-tailed distributions in the data. These can be addressed through a specific choice of pre-processing and/or model components.

In this task, as an illustration of a real-world problem, we are asked to predict the evolution of hospital patients' states and needs during their stay in the Intensive Care Unit (ICU). For each patient, we are provided with the monitoring information collected during the first 12h of their stay. From the data, our first need to extract meaningful features describing this 12h stay. Then, for each sub-task, we should select an appropriate model to train on your pre-processed data. the typical challenges of working with real medical data: missing features and imbalanced classification, predicting rarely-occuring events

need to extract meaningful features describing this 12h stay

evaluate the performance of a model with the Area Under the Receiver Operating Characteristic Curve, which is a threshold-based metric. To achieve good performance, it is important to produce (probabilistic) real-valued predictions in the interval [0, 1].

binary classification



# suppose df is a pandas dataframe containing the result
import pandas as pd

df.to_csv('prediction.zip', index=False, float_format='%.3f', compression='zip')
