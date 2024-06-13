# **Exploratory-Data-Analysis(EDA)**

The scope of this project is to perform an exploratory data analysis(EDA) for the company ABC and generate a comprehensive report detailing information about their employee and various teams.  EDA is the most modern method to do the same. So i have done this project for the company ‘ABC’, following are the main steps to perform EDA.

## **Step 1: Import python libraries.**

Import all libraries which are required analisis, such as  Data loading, Statical analysis, Visualization, Data Transformation, Merge and Join etc.

## **Step 2: Reading Dataset.**

By using pandas library data is loaded into pandas DataFrame from the file .csv, using the function read_csv() data can convert into pandas DataFrame.

## **Step 3: Data Preprocessing.**

The main goal  of data  understanding is to gain general insights about the data, which covers the number of rows and columns, values in the data, data types, and missing values in the data set. 

### **A) Deriving Statistical Summary.**

Statistical summary gives a high-level idea to identify whether the data have any out layers, data entry errors, distribution of data. In python this can be achieved by using function describe(). 

### **B) Checking for duplicate and null values.**

By using the function nunique() checks the values in each column we can identify the continuous and categorical column in the data. Duplicated data can be removed based on further analysis. By using function isnull() we can find the null values in the DataFrame.

### **C) Dropping or Filling data.**

We can drop columns or rows with null values or can fill with 0, mean or median

## **Step 4: Data Analysis.**

Retrieving meaningful insists.

## **Step 5: Data visualisation.**

There are different types of graphs like line, scatter plot, pie, bar, box plot etc for visualisation of data. Matplotlib is a python 2D plotting library used to draw basic charts Seaborn is also a python library built on top of Matplotlib by using the same can create statistical plots from Pandas and Numpy.
