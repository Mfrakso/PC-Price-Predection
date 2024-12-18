# PC-Price-Predection
This project aims to predict the prices of laptops based on various features like RAM, CPU brand, type, weight, and other specifications. The dataset contains information about laptop attributes, and we use machine learning techniques to build a model that predicts laptop prices. We apply preprocessing steps, feature encoding, data scaling, and Linear Regression to build and evaluate the model.

Data Overview:
Total rows: 1,268
Total columns: 16
The dataset contains missing values, which are handled by dropping rows with null values (dropna()).
Label Encoding
Categorical variables (e.g., CPU brand, GPU brand, Company, OS, TypeName) are encoded using LabelEncoder to convert them into numeric values for use in the machine learning model.

3. Standardization
The features are standardized using StandardScaler to scale the data between 0 and 1 for improved performance during training. This is particularly important for algorithms like Linear Regression that are sensitive to feature scaling.
4. Train-Test Split
The data is split into training (67%) and testing (33%) sets using train_test_split.
Model Building
Linear Regression
