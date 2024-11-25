

# House Price Prediction

This project predicts house prices based on various features using a machine learning model. It leverages historical data and employs linear regression to analyze factors such as location, size, and total area to predict property prices.

---

## Table of Contents

1. [Project Overview](#project-overview)  
2. [Technologies Used](#technologies-used)  
3. [Dataset Description](#dataset-description)  
4. [Installation](#installation)  
5. [Usage](#usage)  
6. [Results](#results)  
7. [Contributing](#contributing)  
8. [License](#license)

---

## Project Overview

House prices can vary significantly based on various factors such as location, size, and availability status. This project aims to predict property prices using a dataset of house attributes and machine learning techniques. Linear regression is used as the primary model to provide accurate price predictions.

---

## Technologies Used

- **Python 3.x**  
- Libraries:  
  - `pandas`  
  - `numpy`  
  - `scikit-learn`  
  - `matplotlib` (optional for visualizations)

---

## Dataset Description

The dataset contains the following columns:

- **area_type**: Type of area (e.g., Built-up Area, Plot Area)  
- **availability**: Availability status (Ready to move/Under construction)  
- **location**: Location of the property  
- **size**: Number of bedrooms (e.g., 2 BHK)  
- **total_sqft**: Total area in square feet  
- **bath**: Number of bathrooms  
- **balcony**: Number of balconies  
- **price**: Price of the property (target variable)

### Null Value Handling:
- **size**: Replaced null values with the most frequent category.  
- **bath**: Replaced null values with the median.  
- **balcony**: Replaced null values with the median.

---

## Installation

1. Clone the repository:  
   ```bash
   git clone https://github.com/TejasK1710/House-Price-Prediction.git
   cd House-Price-Prediction
   ```

2. Install the required libraries:  
   ```bash
   pip install -r requirements.txt
   ```

3. Place the dataset in the project directory.

---

## Usage

1. Run the script:  
   ```bash
   python house_price_prediction.py
   ```

2. Follow the instructions in the terminal to load the dataset and start predictions.

3. Modify the dataset or model parameters as needed in the script for custom usage.

---

## Results

The linear regression model demonstrated a good fit for predicting house prices. Visualization tools can be used to assess model performance further.

---

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.  
2. Create a new branch.  
3. Make your changes.  
4. Submit a pull request.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

