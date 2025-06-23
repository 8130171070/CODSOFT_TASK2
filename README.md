📊 Movie Rating Prediction
--
📁 Dataset
Dataset: movie_dataset.csv
Columns: Name, Year, Duration, Genre, Rating, Votes, Director, Actor 1, Actor 2, Actor 3
--
🔥 Problem Statement
Build a model to predict the rating of a movie based on features like Genre, Director, Actors, Year, Duration, and Votes using regression techniques.
--
🚀 Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
--
✅ Steps Performed
📌 Step 1: Imported Required Libraries
📌 Step 2: Loaded Dataset
📌 Step 3: Basic EDA
Checked null values, dataset shape, and statistical summary.
📌 Step 4: Data Preprocessing
Cleaned columns (Votes, Duration, Year).
Handled missing values.
📌 Step 5: Graphical EDA
📊 Plotted Rating Distribution
📊 Plotted Genre Frequency
📊 Plotted Votes vs Rating Scatter Plot
📊 Plotted Duration vs Rating Scatter Plot
✅ Saved all graphs in the images folder.
📌 Step 6: Feature Encoding
Applied One-Hot Encoding to categorical features.
📌 Step 7: Model Building
Trained Linear Regression Model.
📌 Step 8: Model Evaluation
Used Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score.
📌 Step 9: Conclusion
Current model accuracy is low (R² is negative) → more features or advanced models like Random Forest can improve results.
--
📂 Folder Structure
Movie-Rating-Prediction/
│
├── dataset/
│    └── movie_dataset.csv
│
├── images/
│    └── rating_distribution.png
│    └── genre_frequency.png
│    └── votes_vs_rating.png
│    └── duration_vs_rating.png
│
├── notebook.ipynb
├── README.md
--
📊 Final Results
Metric	Value
MAE	1.78
MSE	6.34
R²	-2.41
--
✨ Key Learnings
Cleaned complex categorical and numerical data.
Visualized hidden trends using graphs.
Understood the limitation of Linear Regression on large categorical datasets.
Learned the importance of feature selection and model choice.