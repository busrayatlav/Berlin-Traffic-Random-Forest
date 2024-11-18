# Berlin Traffic Speed Prediction Using Random Forest

This project applies **a Random Forest Regressor to predict average vehicle speed in Berlin based on traffic density data**. By analyzing relationships between vehicle counts (total, cars, trucks) and their speeds, the project provides insights into traffic behavior and performance evaluation of the model.
 
## Table of Contents
1.	Project Description
2.	Dataset
3.	Installation
4.	Usage
5.	Results
6.	Visualizations
7.	Technologies Used
8.	License
 
## Project Description

Accurate prediction of average vehicle speed helps in understanding traffic patterns and improving transportation systems. This project:
-	Trains a Random Forest Regressor using traffic density data.
-	Evaluates the model with metrics like Mean Squared Error (MSE) and R-squared (R²).
-	Visualizes model results and feature importance for interpretability.
 
## Dataset

The dataset contains hourly traffic data from Berlin:
1. Features:
   -vehicle_count_per_hour: Total vehicles per hour.
   - car_count_per_hour: Total cars per hour.
   - truck_count_per_hour: Total trucks per hour.
2. Target:
   - avg_speed_all_vehicles_kmh: Average speed of all vehicles (km/h).
   - The dataset is stored in a CSV file and uses a semicolon (;) as the delimiter.
 
## Installation
1.	Clone the repository:
git clone https://github.com/busrayatlav/Berlin-Traffic-Random-Forest.git
cd Berlin-Traffic-Random-Forest
2.	Set up a Python virtual environment (optional but recommended):
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3.	Install dependencies:
pip install -r requirements.txt
 
## Usage
1.	Load the dataset and ensure it's in the same directory:
   ```bash
   /path/to/berlin_traffic_data.csv

2. Run the script:
  ```bash
  python berlin_traffic_random_forest.py

3.Outputs:
  ```bash
  -	Model performance metrics (MSE, R²) displayed in the terminal.
  -	Visualizations saved or displayed.


## Results
•	Mean Squared Error (MSE): 188.14
•	R-squared (R²): 0.27
•	The model shows moderate predictive accuracy but highlights key features influencing average speed.
 
## Visualizations
1.	Actual vs Predicted Speeds: A scatter plot comparing actual traffic speeds to model predictions. 
2.	Feature Importance: A bar chart showing the relative importance of input features. 
3.	Residual Plot: A scatter plot of residuals to evaluate prediction errors. 
 
## Technologies Used
-	Python: Programming language.
-	Pandas: Data manipulation.
-	scikit-learn: Machine learning library.
-	Matplotlib: Data visualization.
 
## License
This project is licensed under the MIT License.
