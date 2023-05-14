# ResalePricePredictionModel
 Resale Price Prediction Model built via PySpark


HDB flats spell home for 80% of Singapore's resident population, of which about 90% own their home. There are various sizes, and configurations purpose-built across the years, all over the whole island of Singapore.

Many have gotten a flat from the resale market instead of directly from HDB over the years, and these transactions have been compiled regularly by the government.
A modified version of some HDB transactions has been provided for a Resale Price Prediction Model to be built, based on the other available typical characteristics of a transaction, via PySpark.
The file name is “sg_flat_prices_mod.csv”, a single table consisting of 64248 rows, and 12 columns. 

## Steps used to build Resale Price Prediction Model

### Step 1: Problem Statement Formulation
Load the data from the CSV file. Explore the data, understand the data and prepare a problem statement to justify how model could provide value to an organization or to individuals.
- 1.1. Introduction: Problem Understanding
- 1.2. Formulate a Value Based Problem Statement

### Step 2: Exploratory Data Analysis and Data Cleansing

Examine data, and flag out any interesting trends, anomalies, or potential errors.

 - 2.1. Missing Value Treatment
    - 2.1.1. Finding missing value
    - 2.1.2. Dealing with missing value      

 - 2.2.Drop Unnecessary Columns
    - 2.2.1. Lease Commence Date
    - 2.2.2. Town

### Step 3: Data Wrangling and Transformation
Wrangle and/or transform the tabular data before feeding it into the Machine Learning portion
of Predictive Model.

- 3.1. Categorical Encoding
     - 3.1.1. Ordinal Encoding
     - 3.1.2. One-Hot Encoding

- 3.2. Feature Scaling     
     - 3.2.1. No Scaling    
     - 3.2.2. Standard Scaler

### Step 4: Machine Learning Modelling
- 4.1. Count of Rows and Columns    
- 4.2. Sample of 10 Rows before modelling           
- 4.3. Building Predictive Model     


### Step 5: Model Evaluation and Selection
Evaluate the model performance. 

- 5.1. Utilize Model Metrics for Evaluation

### 6. Summary and Further Improvements   
- 6.1. Summarize findings
- 6.2. Explain the possible further improvements
