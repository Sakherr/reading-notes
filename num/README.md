

## Pandas is a Python library that provides high-performance, easy-to-use data structures and data analysis tools for working with structured (tabular, multidimensional, potentially heterogeneous) and time series data. It is built on top of the NumPy array library and the Cython language extension.

# operations that can be performed on data using Pandas include:

## Data cleaning: This involves removing or correcting errors in the data.
## Data transformation: This involves changing the format or structure of the data.
## Data analysis: This involves performing statistical analysis on the data.
## Data visualization: This involves creating charts and graphs to display the data.
## The primary data structures in Pandas are the Series and the DataFrame.

## A Series is a one-dimensional data structure that can hold any data type, such as numbers, strings, or dates.

## A DataFrame is a two-dimensional data structure that can hold multiple Series.

## The Series and the DataFrame are both very flexible data structures that can be used for a variety of tasks.

## To load a dataset into a Pandas DataFrame, you can use the read_csv() function. This function can read data from a variety of file formats, including CSV, JSON, and XML.

##  example of how to load a dataset into a Pandas DataFrame:
``` 
import pandas as pd

df = pd.read_csv('data.csv')
Use code with caution. Learn more
This will create a DataFrame called df that contains the data from the data.csv file.
``` 
#  common file formats that can be used with Pandas:

## CSV: This is a comma-separated value file format.
## JSON: This is a JavaScript Object Notation file format.
## XML: This is an Extensible Markup Language file format.

# Pandas functions that are utilized to read these file formats:

read_csv()
read_json()
read_xml()