***Data Loading and Exploration***:

Loads customer financial data and provides a preliminary exploration, such as checking for missing values and examining column details.

Uses pandas and numpy to manipulate the data and visualize relationships.

***Feature Engineering and Visualization***:

Maps qualitative features like Credit_Mix to numerical values for analysis.

Utilizes seaborn to create boxplots that compare credit scores with features like age, annual income, and the number of credit cards.

***Machine Learning Model***:

Extracts key features from the dataset for training and testing.

Splits data into training and testing sets using train_test_split.

Trains a RandomForestClassifier model on the training data and evaluates its performance on the test set.

***Credit Score Prediction Interface***:

Prompts users to input relevant financial details for a live prediction.

Takes features like annual income, number of loans, and outstanding debt, feeding them into the trained model to predict the customer's credit score.
