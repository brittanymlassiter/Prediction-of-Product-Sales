# Prediction of Product Sales

Brittany Lassiter

## Analyzing various features over numerous stores and how it affects sales for different food items. 

## What the Business wants to know.
- Our retailers wants to understand the properties of products and outlets that play crucial roles in increasing their sales.

## Data Collected
There are 8523 rows and 7 columns of data collected to help highlight procductions. Data was collected given from the Coding Dojo's Data science program. 

## Data Dictionary

| Variable Name             | Description                                                                                         |
|---------------------------|-----------------------------------------------------------------------------------------------------|
| Item_Identifier           | Unique product ID                                                                                   |
| Item_Weight               | Weight of product                                                                                   |
| Item_Fat_Content          | Whether the product is low fat or regular                                                           |
| Item_Visibility           | The percentage of total display area of all products in a store allocated to the particular product |
| Item_Type                 | The category to which the product belongs                                                           |
| Item_MRP                  | Maximum Retail Price (list price) of the product                                                    |
| Outlet_Identifier         | Unique store ID                                                                                     |
| Outlet_Establishment_Year | The year in which store was established                                                             |
| Outlet_Size               | The size of the store in terms of ground area covered                                               |
| Outlet_Location_Type      | The type of area in which the store is located                                                      |
| Outlet_Type               | Whether the outlet is a grocery store or some sort of supermarket                                   |
| Item_Outlet_Sales         | Sales of the product in the particular store. This is the target variable to be predicted.          |

## To prepare this data, data was cleaned and proccessed for missing or incomplete data. Sci-Kit Learn's SimpleImputer was used on the training data set in order to prevent data leakage. 

  
## As shown below, is a correlation's map, demostrating different measurements to highlighting the variables to link properties for a better understanding of the data.

![image](https://github.com/brittanymlassiter/Prediction-of-Product-Sales/assets/141593737/24b05895-46db-4c7d-8b2a-2aed63ba071c)



## Visualizating through a countplot graph, the Item Fat Content variable was used to further demonstrate products affects of sales productions. It shows thats the Low Fat items has the greatest sales overall. 

![image](https://github.com/brittanymlassiter/Prediction-of-Product-Sales/assets/141593737/c14b9c3c-ec6f-435d-a50f-417870476553)


## What is determined
- The top 3 impactfful features are their locations. As shown below, the most impactful locations are the Outlet_location_type_tier 1, Outlet_location_type_tier 3, and the Outlet_identifier.
  
  ![log importance](https://github.com/brittanymlassiter/Prediction-of-Product-Sales/assets/141593737/b3bb6768-4c6a-4a9d-9f1e-e2db2ffff94f)

- The top 5 most important features are the Item MRP, Item Visibilty, Item Weight, Outlet_Identifier, and Outlet type grocery store.

  ![random](https://github.com/brittanymlassiter/Prediction-of-Product-Sales/assets/141593737/6bb8823f-b848-400c-af53-f387c17e192d)



 ### Statement
- This dataset/models shows the locations with the greatest impact include Outlet_location_type_tier 1, Outlet_location_type_tier 3, and Outlet_identifier.



#### For Further information
For additioal questions, please contact me at blassiter54@gmail.com
