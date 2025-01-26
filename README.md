# *Project on Any kind of Data_set*

First of all, I select the **laptop_purchase_data_india**, from the kaggle.com.
The format of the file is csv. I am going to perform different operation on that dataset by using pandas library. 
Those operations are given below:

- Data Load
- Data Cleaning
- Data Preprocessing
- Data Augmentation, and
- Data save


## Data Load
Now starting with the data load, it means that how we can load data or read the data of excel file by using pandas. Data Load involves different functions() to perform.
We can categorise them into different parts:

1. **Inspecting the Data:**
   - Index
   - head()
   - tail()
   - sample()


2. **Checking the Structure:**
    - info()
    - shape
    - columns
3. **Basic Calculations:**
    - sum()
    - min()
    - max()
    - mean()

4. **Descriptive Statistics:**
    - describe()
    - nunique()
    - value_counts()


5. **Viewing the Data:**
    - iloc[ ]
    - loc[ ]
  

6. **Quick Visualization:**
    - plot()
      1. bar 
      2. Horizontal bar
      3. line
      4. Histogram
      5. Box
      6. pie 
      7. Density
---

## Data Cleaning
Data cleaning in pandas refers to the process of preparing and correcting your dataset by handling issues like missing values and duplicate data. Data cleaning also involves different functions and they are categorised as according to their use:

1. **Handle Missing Data:**
    - isnull()
    - notnull()
    - column addition
    - fillna()
    - dropna()
    

2. **Removing Data:**
    - duplicated()
    - drop_duplicates()
    - drop()


3. **Renaming Columns:**
    - rename()


4. **Converting Datatype:**
    - astype()

---

## Data Preprocessing

Data preprocessing means that to convert or show your raw data in a well-mannered or structured way that will helps in to analyze the Data_set.
Here's a breakdown of what it involves:

- groupby()


---


## Data Augmentation
Data augmentation is the process of artificially increasing the size and diversity of a dataset by applying transformations or generating synthetic data.
It is commonly used in machine learning, especially in scenarios like image processing, text analysis etc. There are three types of techniques that we can used for data augmentation:

- For Images
- For Text Data
- For Tabular Data

Everey technique have different functions. Because our data is in csv format so we have to apply the tabular technique on that.
Different functions of tabular technique includes:

- repeat()
- DataFrame()
- concat()
- merge()
  
----

## Data save
Data saving in pandas refers to the process of storing data from a pandas DataFrame into various file formats, such as CSV, Excel, or SQL databases,
after performing necessary operations or modifications. Saving the data allows you to keep the processed or clean data for future analysis or sharing.
If you want to save your file wether it's a CSV file or other files like Excel, JSON, SQ you just have to specify the format of the file and the name of the file.
For Example: 
If you want to save your CSV file, then:

-  df.to_csv("file_name.csv")

By default, It saves the index of the file also but if you did'nt want that then you can just add a command in the function, like:
- df.to_csv("file_name.csv" , index= False)
  
---
