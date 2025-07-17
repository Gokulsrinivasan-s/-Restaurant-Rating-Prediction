Restaurant-Rating-Prediction
(Cognifyz ML Internship)

1)Task Objective:

This task focuses on building a Machine Learning model that predicts the aggregate rating of a restaurant based on various features like:
City
Price Range
Cuisines
Votes
Online Ordering
Table Booking Availability

2)Technologies Used:

Python
Pandas
Scikit-learn
Matplotlib / Seaborn (for visualization)
Jupyter Notebook / Google Colab

3)Project Structure

Copy
Edit
├── dataset.csv
├── task1_rating_prediction.ipynb
├── README.md

4)Steps Performed:

1)Import Dataset
Load the restaurant dataset using pandas.

2)Clean Dataset
Remove missing or duplicate values.

3)Convert Text to Numbers
Label encode categorical features like City, Cuisines, etc.

4)Select Features and Target
Features: City, Price Range, Votes, etc.
Target: Aggregate Rating

5)Split Data
Split into training and testing sets (e.g., 80% train, 20% test).

6)Train ML Model
Use RandomForestRegressor to train the model.

7)Evaluate the Model
print("Mean Squared Error:", mse)
print("R-squared:", r2)
User Input Prediction
Predict the rating of a restaurant based on custom user input.

5)Example Output:

Mean Squared Error: 0.12
R-squared: 0.89
Predicted Rating for Input Restaurant: 4.2

6)Project Outcome:

Successfully built and evaluated a regression model to predict restaurant ratings.
Learned data preprocessing, feature encoding, and model evaluation techniques.

7)Output:

<img width="1360" height="768" alt="Image" src="https://github.com/user-attachments/assets/4db042ee-a426-4b3d-9855-62aa14fdecb2" />
<img width="1360" height="768" alt="Image" src="https://github.com/user-attachments/assets/d9ad86a8-728d-4dc5-9f6d-6bbdb390963e" />
<img width="1360" height="768" alt="Image" src="https://github.com/user-attachments/assets/838caf64-e7b0-443c-be8b-54ad575d4007" />


