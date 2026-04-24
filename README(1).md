# Prediction-of-Product-Sales
## Sales Analysis and Forecasting for Data-Driven Insights 

**Author**: YazanM (Eng.Yazan Maghary)

### Business problem:

* Retail Bussiness need to predict future sales
* The goal is to build model to predict sales
* This help for planning and decision making

### Data:

* Data Source : [Big Mart Sales Dataset](https://www.analyticsvidhya.com/datahack/contest/practice-problem-big-mart-sales-iii/)
* rows = 8532  entries
* Features = 12 columns (Exluding the target)
* float(4) , int(1) , str(7)
* Target = Item_Outlet_Sales

## Methods
- Load The Data
- Clean Data (handling missing values, duplicates)
- Exploratory data analysis
- Feature Inspection
- Splitting and training the data
- Modeling 

## Results

#### Item outlet sales frequency

<img width="300" height="300" alt="Item_Outlet_Sales" src="https://github.com/user-attachments/assets/ff632532-0e6e-48e4-afd2-eddd77b3bb15" />


##### From the histogram graph we can show and notice that :

* most frequent items is between 0 to 2000 that mean that the most of sales are between 0 to 2000
* this Right-Skewed Distribution
* when the item price rise we notice that the number of sales decrease whic mean that items with lower price has more sales that higher price


#### Heatmap correlation

<img width="300" height="300" alt="HeatMap" src="https://github.com/user-attachments/assets/6b3d651c-b503-4804-b24c-51e7dc6236d4" />


##### From the HeatMap graph we can show and notice that :

* The Graph show the relation between numrical objects in the data set
* from the correlation we notice that there isn't strong relations in the data set

#### Item MRP vs Item outlet sales

<img width="469" height="325" alt="output1" src="https://github.com/user-attachments/assets/6c439760-37af-4f5a-9ce9-3ebf124727e6" />

##### Feature vs. Target Observations:
  * Based on your business understanding, would you expect this feature to be a predictor of the target?
    * Yes , based on business understanding, Item_MRP can be a predictor of sales. In fact, when item MRP is high, sales tend to be Higher
  * Does this feature appear to be a predictor of the target?
    * Yes , There is a positive correlation between Item_MRP and Item_Outlet_Sales

#### Outlet type vs item outlet sales

<img width="467" height="307" alt="output8" src="https://github.com/user-attachments/assets/ec0e2862-aeb1-4429-b7a1-545dc0f6f081" />


##### Feature vs. Target Observations:
  * Based on your business understanding, would you expect this feature to be a predictor of the target?
    * Yes , based on business understanding, Outlet_Type can be impact the item_outlet_sales
  * Does this feature appear to be a predictor of the target?
    * Yes , The mean of sales have different value when Outlet_Type change , Grocery the lowest , type 3 is the highest , so its can be a predictor of the target
      
## Model

* We decide after a lot of imputation and evaluation to process and choose the random forest model tuned with cusom parameters
### Model Metrics :

<img width="399" height="149" alt="Image" src="https://github.com/user-attachments/assets/06b9535f-35d5-4755-984b-b4569f488ed2" />

* Model Interpretation: 
   * Our model is berform will with r2_score 0.666 for training set and 0.598 for testing set thats mean that our model will predict the price With 66.6% accuracy for training set and 59.8% accuracy for testing set
* choosing MAE :
   * i choose it for showing the stakeholder that the predicted price are off about 742 units than the real price , and that know as average absolute error
* after choosing best parameters the r2_score for training set is 0.666 and r2_score for testing set is 0.598 ,so there is no overfitting or underfitting or there is only very low difference between r2_score for training set and r2_score for testing set

## Recommendations:

- Enhance the dataset by adding new features with strong correlation to the target variable to improve prediction accuracy.
- Tune hyperparameters using GridSearchCV or RandomizedSearchCV to improve model performance.
- Apply proper scaling/normalization where needed.
- Increase dataset size if possible to improve model robustness.
- Continuously monitor and retrain the model with new data.

## Limitations & Next Steps

- Prediction errors are relatively high (RMSE ≈ 1053 on test data), which may affect business decisions.
- Data quality issues (e.g., missing values, inconsistencies) may impact model performance.
- Feature havn't strong relation or impacts on target.
* Next Step is to adding more fetaure and increasing data set rows to analyze more data with new strong related to target features 

### For further information


For any additional questions, please contact **maghary.yazan@gmail.com**
