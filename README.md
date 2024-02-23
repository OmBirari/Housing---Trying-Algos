<h1>Code Overview</h1>
The code is organized into the following sections:

<h3>1. Data Retrieval</h3>
The housing data is fetched from an external source and loaded into a Pandas DataFrame. The dataset includes information such as longitude, latitude, housing median age, total rooms, total bedrooms, population, households, median income, median house value, and ocean proximity.


<h3>2. Data Exploration</h3>
Various exploratory data analysis (EDA) techniques are employed to understand the dataset. This includes checking basic information, value counts, statistical summaries, and visualizations.


<h3>3. Data Preprocessing</h3>
Data is cleaned and prepared for machine learning algorithms. Missing values are handled, and categorical features are encoded using one-hot encoding. Additionally, attribute combinations are created for better model performance.


<h3>4. Model Training and Evaluation</h3>
Linear Regression -
A simple Linear Regression model is trained and evaluated.<br>
Decision Tree -
A Decision Tree model is trained and evaluated.<br>
Random Forest -
A Random Forest model is trained and fine-tuned using grid search.<br>


<h3>5. Model Testing</h3>
The best-performing model (Random Forest) is tested on the test set, and performance metrics such as root mean squared error (RMSE) are calculated.<br>


<h2>Results</h2>
The final model's performance is summarized, including feature importance. The README provides insights into how to interpret and use the trained model.

Feel free to explore the Jupyter Notebook for a detailed walkthrough of the entire analysis process. Also the code is in progress and I will keep updating it as I keep learning. <br>Cherios !!!
