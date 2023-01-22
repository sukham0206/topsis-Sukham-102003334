# Topsis_Sukham_102003334
This is a python package used to implement TOPSIS(Technique of Order Preference Similarity to the Ideal Solution) for MCDA(Multiple criteria decision analysis)

<br>

## How to use this package:

pip install topsis-sukham-102003334

### In Command Prompt
```
>> topsispy data.csv "1,1,1,1" "+,+,-,+" out.csv
```
## Sample dataset

Model | Correlation | R<sup>2</sup> | RMSE | Accuracy
------------ | ------------- | ------------ | ------------- | ------------
M1 |	0.79 | 0.62	| 1.25 | 60.89
M2 |  0.66 | 0.44	| 2.89 | 63.07
M3 |	0.56 | 0.31	| 1.57 | 62.87
M4 |	0.82 | 0.67	| 2.68 | 70.19
M5 |	0.75 | 0.56	| 1.3	 | 80.39

## Output
This will be in our Output csv file
Model | Correlation | R<sup>2</sup> | RMSE | Accuracy | TOPSIS SCORE | Rank
------------ | ------------- | ------------ | ------------- | ------------ | ------------ | ------------
M1 |	0.79 | 0.62	| 1.25 | 60.89 | 0.77 | 2.0
M2 |  0.66 | 0.44	| 2.89 | 63.07 | 0.23 | 5.0
M3 |	0.56 | 0.31	| 1.57 | 62.87 | 0.44 | 4.0
M4 |	0.82 | 0.67	| 2.68 | 70.19 | 0.52 | 3.0
M5 |	0.75 | 0.56	| 1.3	 | 80.39 | 0.81 | 1.0
