## Gold_Recovery_Prediction
Develop a machine learning model to predict the efficiency of gold recovery at  critical stages of mineral processing
# Introduction:
In this project, the aim is to develop a machine learning model to predict the efficiency of gold recovery at two critical stages of mineral processing:

Rougher recovery — an early separation step

Final recovery — the overall output quality after purification.

The data includes time-indexed measurements from a flotation-based extraction plant, including chemical reagent flows, air volumes, and concentrations of metals such as gold (Au), silver (Ag), and lead (Pb) at various process stages.

Our goal is to build a model that can accurately estimate recovery rates using only the features available in advance (i.e., no future-leaking columns). Special care is taken to:

Validate target correctness,

Handle missing data and anomalies,

Respect the temporal nature of the data through time-based cross-validation, and

Use appropriate evaluation metrics, specifically sMAPE, to align with business requirements.
