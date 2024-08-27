# Delhi House Price Prediction

## Project Overview
The **Delhi House Price Prediction** project is designed to estimate house prices across various localities in Delhi. The objective is to create a predictive model that accurately forecasts house prices based on multiple features. Using a dataset from Kaggle, which includes information on factors such as area, number of bedrooms, and locality, this project aims to offer valuable insights for both buyers and sellers in the real estate market.

## Data Dictionary
The dataset utilized for this project consists of 1259 rows and 11 columns. Here’s a brief description of each column:

| Column Name   | Description                                              |
|---------------|----------------------------------------------------------|
| `Area`        | Area of the house in square feet                        |
| `BHK`         | Number of bedrooms                                      |
| `Bathroom`    | Number of bathrooms                                     |
| `Furnishing`  | Furnishing status                                       |
| `Locality`    | Locality of the house                                   |
| `Parking`     | Number of parking spaces available                      |
| `Price`       | Price of the house in INR                               |
| `Status`      | Property's status (ready to move or under construction) |
| `Transaction` | Whether it's a new property or a re-sale                |
| `Type`        | Type of the property                                    |
| `Per_Sqft`    | Price per square foot                                   |

## Impact
The **Delhi House Price Prediction** project has significant implications for the real estate market:

1. **Buyer and Seller Insights**:
   - Buyers can make informed decisions based on predicted house prices.
   - Sellers can strategize pricing more effectively using model insights.

2. **Exploratory Data Analysis (EDA)**:
   - Revealed key factors influencing house prices, such as area, number of bedrooms, and locality.
   - Identified high-end localities like Punjabi Bagh, Lajpat Nagar, and Vasant Kunj with elevated property prices.
   - Noted a preference for new builder floor properties, indicating buyer demand for customization and independence.

3. **Machine Learning Models**:
   - Employed regression models including Decision Tree Regressor and Random Forest Regressor.
   - The Random Forest Regressor achieved an accuracy of 84.98%, outperforming the Decision Tree Regressor.

## Files
- **`Delhi House Price Prediction.ipynb`**: Jupyter notebook with model development, analysis, and insights.
- **`MagicBricks.csv`**: Dataset used for analysis and model training.

## How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/AshwaniTiwari664/Delhi-House-Price-Prediction
    ```

2. Navigate to the project directory:
    ```bash
    cd Delhi-House-Price-Prediction
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Open the Jupyter notebook:
    ```bash
    jupyter notebook Delhi\ House\ Price\ Prediction.ipynb
    ```

5. Follow the instructions in the notebook to explore the data, build the model, and make predictions.

## License
This project is licensed under the MIT License. See the [LICENSE.md](LICENSE.md) file for details.
