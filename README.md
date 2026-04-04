# Prediction-of-Product-Sales
* The Product Sales Prediction project focuses on identifying key relationships within retail data to forecast future sales performance. The workflow begins with rigorous data cleaning, including handling missing values and removing duplicates to ensure a high-quality dataset.
Once the data is refined, Exploratory Data Analysis (EDA) and advanced visualizations are used to uncover hidden patterns and correlations. This deep understanding of the data's structure and relationships serves as the foundation for building accurate and reliable predictive models.
<img width="300" height="300" alt="Item_Outlet_Sales" src="https://github.com/user-attachments/assets/ff632532-0e6e-48e4-afd2-eddd77b3bb15" />

#### From the histogram graph we can show and notice that :
* most frequent items is between 0 to 2000 that mean that the most of sales are between 0 to 2000
* this Right-Skewed Distribution 
* when the item price rise we notice that the number of sales decrease whic mean that items with lower price has more sales that higher price

<img width="300" height="300" alt="HeatMap" src="https://github.com/user-attachments/assets/6b3d651c-b503-4804-b24c-51e7dc6236d4" />

#### From the HeatMap graph we can show and notice that :
* The Graph show the relation between numrical objects in the data set
* from the correlation we notice that there isn't strong relation in the data set
<img width="300" height="300" alt="Item_MRP Boxplot" src="https://github.com/user-attachments/assets/65663262-7721-4da5-8bb7-08b632330c1a" />

#### From the BoxPlot graph we can show and notice that :
* the sales is frequent betwwen 0 to 6000 that mean that the most of sales are between 0 to 6000
* mean is almots 2000
* there is a lot of outliers begining from 6000
* the graph skewed to the right 
* about 25% of your sales are below 800
* about 50% of your sales are below 2000
* about 75% of your sales are below 3500
<img width="469" height="325" alt="output1" src="https://github.com/user-attachments/assets/6c439760-37af-4f5a-9ce9-3ebf124727e6" />

#### From the BoxPlot graph we can show and notice that :
* Feature vs. Target Observations:
  * Based on your business understanding, would you expect this feature to be a predictor of the target?
    * `...` Yes , based on business understanding, Item_MRP can be a predictor of sales. In fact, when item MRP is high, sales tend to be Higher
  * Does this feature appear to be a predictor of the target?
    * `...` ? Yes , There is a positive correlation between Item_MRP and Item_Outlet_Sales
<img width="467" height="307" alt="output8" src="https://github.com/user-attachments/assets/ec0e2862-aeb1-4429-b7a1-545dc0f6f081" />

* Feature vs. Target Observations:
  * Based on your business understanding, would you expect this feature to be a predictor of the target?
    * `...` Yes , based on business understanding, Outlet_Type can be impact the item_outlet_sales
  * Does this feature appear to be a predictor of the target?
    * `...` ? Yes , The mean of sales have different value when Outlet_Type change , Grocery the lowest , type 3 is the highest , so its can be a predictor of the target

___

