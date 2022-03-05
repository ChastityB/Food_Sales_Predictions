# Food_Sales_Predictions

### Summary

This dataset was imported, cleaned, and visualized. The purpose of this is to help the retailer understand the properties of products and outlets that play crucial roles in predicting sales. 


### Data Dictionary 
| Variable Name | Description |
| --- | --- |
| Item_Identifier | Unique product ID|
| Item_Weight | Weight of product|
| Item_Fat_Content | Whether the product is low fat or regular |
| Item_Visibility | The percentage of total display area of all products in a store allocated to the particular product |
| Item_Type | The category to which the product belongs |
| Item_MRP | Maximum Retail Price (list price) of the product |
| Outlet_Identifier | Unique store ID |
| Outlet_Establishment_Year| The year in which store was established|
| Outlet_Size | The size of the store in terms of ground area covered |
| Outlet_Location_Type | The type of area in which the store is located|
| Outlet_Type | Whether the outlet is a grocery store or some sort of supermarket |
| Item_Outlet_Sales| Sales of the product in the particular store. This is the target variable to be predicted.|

## Data Cleaning
* Fix inconsistency of values

## Data Visualization
* Created plots to determine what factors affected sales

## Machine Learning Model
* Categorical values oneHotEncoded
* Numerical values Scaled

## Model Comparison
* Linear Regression
* Decision Tree Regressor
* Bagged Tree Regressor
* Random Tree Regressor

## Comparing MAE, MSE, RMSE and R2 for Each Regression
### Linear Regression
| Evaluation Metrics | Train Evaluation | Regression |
| --- | --- | --- |
| MAE: | 847.1287 | 804.1187 |
| MSE: | 1297558.3347 | 1194345.9314 |
| RMSE: | 1139.1042 | 1092.8614 |
| R2: | 0.5616 | 0.5671 |

### Decision Tree Regressor
| Evaluation Metrics | Train Evaluation | Regression |
| --- | --- | --- |
| MAE: | 762.6102 | 738.3173 |
| MSE: | 1172122.7729 | 1118185.9731 |
| RMSE: | 1082.6462 | 1057.4431 |
| R2: | 0.6039 | 0.5947 |

### Bagging Tree Regressor
| Evaluation Metrics | Train Evaluation | Regression |
| --- | --- | --- |
| MAE: | 295.4522 | 768.4164 |
| MSE: | 179287.2355 | 1216778.5169 |
| RMSE: | 423.4232 | 1103.0768 |
| R2: | 0.9394 | 0.5589 |

### Random Tree Regressor
| Evaluation Metrics | Train Evaluation | Regression |
| --- | --- | --- |
| MAE: | 755.3756 | 728.3529 |
| MSE: | 1152604.3991 | 1096354.0177 |
| RMSE: | 1073.5942 | 1047.0693 |
| R2: | 0.6105 | 0.6026 |
