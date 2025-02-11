# Food Order Prediction for Online Food Delivery Business

## Problem Statement
The task is to predict the number of food orders for an online food delivery business at each of their branches for a particular week in the future. This solution helps in planning just-in-time procurement of ingredients, reducing wastage, and optimizing costs.

---

## Data Overview
The project involves three datasets containing information about transactions, branch details, and meal properties.

### 1. Transaction Data
| Column               | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| `id`                 | Unique transaction ID                                                      |
| `week`               | Week number (training data includes weeks 1 through 145)                  |
| `center_id`          | Unique identifier for the branch of the food delivery business            |
| `meal_id`            | Unique identifier for the meal                                             |
| `checkout_price`     | Price of the meal after discounts and coupons                              |
| `base_price`         | Base price of the meal                                                     |
| `emailer_for_promotion` | Boolean indicating if the meal was promoted via email                     |
| `homepage_featured`  | Boolean indicating if the meal was featured on the homepage                |
| `num_orders`         | **Target variable:** Number of orders placed                               |

### 2. Branch Information
| Column       | Description                                                             |
|--------------|-------------------------------------------------------------------------|
| `center_id`  | Unique identifier for the branch of the food delivery business         |
| `city_code`  | Unique identifier for the city in which the branch operates            |
| `region_code`| Unique identifier for the region in which the branch operates          |
| `center_type`| Categorical variable for the branch type                               |
| `op_area`    | Operating area of the branch                                           |

### 3. Meal Information
| Column       | Description                                        |
|--------------|----------------------------------------------------|
| `meal_id`    | Unique identifier for the meal                    |
| `category`   | Category of the meal                               |
| `cuisine`    | Cuisine type (categorical variable)               |

---

## Project Structure
- **Data:** Contains the training, validation, and test datasets.
- **Notebooks:** Jupyter notebooks for EDA, feature engineering, and model development.
- **Models:** Trained models and serialized objects.
- **Scripts:** Core functions for preprocessing, model training, and prediction.
- **README.md:** Comprehensive project documentation.

---

## Goals and Deliverables
- **Data Analysis:** Identify trends and relationships in historical transaction data.
- **Feature Engineering:** Develop features that capture relevant patterns.
- **Model Development:** Train machine learning models to accurately predict future food orders.
- **Evaluation:** Measure performance using appropriate metrics.
- **Deployment:** Provide a scalable solution for real-time prediction.

---

Feel free to customize or expand the README as you add more insights and details to your project!

