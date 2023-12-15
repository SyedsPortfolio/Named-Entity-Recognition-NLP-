# Named Entity Recognition (using NLP)

![What-Is-Named-Entity-Recognition-NER-and-What-Can-You-Do-with-It-980x551 png](https://github.com/SyedsProjectPortfolio45/Named-Entity-Recognition-NLP-/assets/147240839/753d2238-f9de-4075-80bb-48997a86f988)

#### Tools used🛠: Python, ML, NLP, NumPy, Pandas, Sk-learn, TensorFlow, Keras, spaCy
🔗dataset link -->https://raw.githubusercontent.com/amankharwal/Website-data/master/ner_dataset.csv 

## 🚧You see the detailed code with visualizations by clicking on the Google Colab logo when you open the ipynb file

# Objective
My aim is to build a ML model that tries to recognize and classify multi-word phrases with special meaning, e.g. people, organizations, places, dates, etc.

# How it works
For example, we want to monitor the news for mentions of Covid-19 patients and for each patient we need the name of the responsible medical organization, location and date.

The Named Entity Recognition task attempts to correctly detect and classify text expressions into a set of predefined classes. Classes can vary, but very often classes like people (PER), organizations (ORG) or places (LOC) are used.

## Step-by-step approach
- Imported necessary Python libraries and Dataset
- Checked for null values
- Performed **EDA**
- Conducted Data Exploration by visualizing **box-plots** of credit scores based on occupation, annual salary, monthly inhand salary, number of bank accounts, number of credit cards, average interest rates, number of loans taken, days delayed for credit card payments, number of delayed payments, number of outstanding debt, credit utilization ratio, credit history age, total number of EMI's per month, amount invested monthly, monthly balance left.
- Created a Credit Mix column categorically by transforming it into numerical feature so that we can use it to train a Machine Learning model for the task of credit score classification
- Split the data into training and test sets and proceed further by training a credit score classific
