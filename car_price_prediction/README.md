# Car Price Prediction

## Project Overview
The **Car Price Prediction** project aims to develop a machine learning model that accurately predicts the resale price of used cars based on various attributes such as brand, model, year, engine size, fuel type, transmission, mileage, number of doors, owner count, and more. This dataset is ideal for price prediction models and market analysis, revealing trends such as depreciation patterns and the rising popularity of hybrid and electric vehicles.

## Dataset Description
The **Car Price Dataset** contains **10,000 records** with **10 attributes** detailing used cars and their resale prices.

### Columns in the Dataset:
- **Brand (object)**: The car manufacturer (e.g., Kia, Chevrolet, Mercedes, Audi, etc.).
- **Model (object)**: The specific model of the car.
- **Year (int64)**: The manufacturing year of the car (range: 2000 to 2023).
- **Engine_Size (float64)**: The size of the engine in liters (range: 1.0L to 5.0L).
- **Fuel_Type (object)**: The type of fuel used (e.g., Diesel, Hybrid, Electric).
- **Transmission (object)**: The type of transmission (e.g., Manual, Automatic, Semi-Automatic).
- **Mileage (int64)**: The total distance the car has traveled, in kilometers (range: 25 to 299,947).
- **Doors (int64)**: The number of doors (range: 2 to 5).
- **Owner_Count (int64)**: The number of previous owners (range: 1 to 5).
- **Price (int64)**: The selling price of the car in USD.

### Insights from the Dataset:
- Newer cars, luxury brands, and lower mileage vehicles generally have higher prices.
- Automatic, diesel, and hybrid cars tend to be more valuable.
- The dataset reveals depreciation patterns and the growing demand for hybrid and electric vehicles due to environmental concerns.

## Usage
This dataset can be used for:
- Developing **machine learning models** for car price prediction.
- Conducting **market analysis** to identify pricing trends.
- Understanding factors affecting the resale value of cars.

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/car_price_prediction.git
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the analysis:
   ```sh
   python main.py
   ```
