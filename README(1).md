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

Describe your final model

Report the most important metrics

Refer to the metrics to describe how well the model would solve the business problem

## Recommendations:

More of your own text here


## Limitations & Next Steps

More of your own text here


### For further information


For any additional questions, please contact **email**
