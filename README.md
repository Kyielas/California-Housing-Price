# California-Housing-Price-Regression

<img src='capstone-m3-coverphoto-min.png'>

## **Context**:

In today's competitive housing market, accurately predicting house prices is crucial for both buyers and sellers. Accurately forecasting house values empowers buyers with informed financial decisions while helping sellers optimize their profit margins. This is where predictive modeling comes in, and one relevant domain is the California housing market, where diverse factors influence property values.

## **Problem Statement**:

The primary challenge lies in developing a robust and accurate model that predicts median house values in California, considering the multitude of factors impacting housing prices. These factors encompass geographical attributes like latitude and longitude, demographic features like population and households, and housing-specific characteristics like total rooms, bedrooms, and age. The goal is to build a model that can capture these diverse influences and reliably predict median house values in different Californian localities.

## **Goals**:

**Accurate Median House Value Prediction:**

- Develop a robust model that predicts median house values in California with high accuracy, achieving low Mean Absolute Error (MAE), Mean Squared Error (MSE), and Median Absolute Percentage Error (MAPE).
- Ensure the model generalizes well to unseen data across diverse Californian localities, capturing the influence of geographical, demographic, and housing-specific features.

## **Metric Evaluation**:

1. Mean Absolute Error (MAE): Measures the average absolute difference between predicted and actual house values. A lower MAE indicates better model performance.

2. Mean Squared Error (MSE): Measures the average squared difference between predicted and actual house values. A lower MSE indicates better model fit.

3. Median Absolute Percentage Error (MAPE): Measures the median percentage difference between predicted and actual house values as a percentage of the actual values. A lower MAPE indicates better model accuracy relative to the actual house values.

## **Data Information**

| **Feature**         | **Description**                                          |
|---------------------|----------------------------------------------------------|
| `Longitude`         | Geographic coordinates of the house.                     |
| `Latitude`          | Geographic coordinates of the house.                     |
| `HousingMedianAge`  | Median age of houses in the neighborhood.                 |
| `TotalRooms`        | Total number of rooms in the house.                      |
| `TotalBedrooms`     | Total number of bedrooms in the house.                   |
| `Population`        | Population of the neighborhood.                          |
| `Households`        | Number of households in the neighborhood.               |
| `MedianIncome`      | Median income of households in the neighborhood.         |
| `MedianHouseValue`  | Median value of houses in the neighborhood.              |
| `OceanProximity`    | Proximity of the house to the ocean.                      |

## Getting Started

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Kyielas/California-Housing-Price-Regression.git
