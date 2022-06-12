# prediction-missing-values

missing values, an imbalance of the labels, or heavy-tailed distributions in the data. These can be addressed through a specific choice of pre-processing and/or model components.

need to extract meaningful features describing this 12h stay

evaluate the performance of a model with the Area Under the Receiver Operating Characteristic Curve, which is a threshold-based metric. To achieve good performance, it is important to produce (probabilistic) real-valued predictions in the interval [0, 1].

binary classification



# suppose df is a pandas dataframe containing the result
import pandas as pd
df.to_csv('prediction.zip', index=False, float_format='%.3f', compression='zip')
