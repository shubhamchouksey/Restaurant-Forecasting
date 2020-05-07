# Restaurant-Forecasting
 Predict top 'Menu Item' and 'Item Qty' for lunch and dinner. These predictions need to be for future dates (Monday to Sunday, July 1st to July 7th)

## Methods Used
- Machine Learning
- Data Visualization
- Predictive Modeling
## Technologies
- Python
- Keras
- Pandas, jupyter

## Data  
**Restaurent.csv**
- The dataset is for restaurant sales for Friday and Saturday, both lunch and dinner time. There are few instances of 'To-Go' orders like Uber Eats in this dataset.
- The columns are self-explanatory
- typical lunch hour is 11:30AM-2:00PM, and dinner hour is 6:30PM-10:00PM
- `item_qty` is the target fields and `shift`, `party_size`, `menu_category`, `menu_item`, `item_price` are Features fields.

We need to predict the menu item and item quantity in the duration: July 1st, 2019 to July 7th, 2019. 

## Getting Started
1. Clone this repo    

2. See [Notebook 1: PredictResto](https://github.com/shubhamchouksey/Restaurant-Forecasting/blob/master/PredictResto.ipynb) to examine raw data, EDA, preliminary cleaning steps, feature engineering, modeling, and evaluation of predictions.

## Result:

![](https://github.com/shubhamchouksey/Restaurant-Forecasting/blob/master/Figure/paper_fig_2.png)
