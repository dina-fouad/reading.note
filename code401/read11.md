## What is Jupyter Lab
JupyterLab is a next-generation web-based user interface for Project Jupyter.

JupyterLab enables you to work with documents and activities such as Jupyter notebooks, text editors, terminals, and custom components in a flexible, integrated, and extensible manner.

You can arrange multiple documents and activities side by side in the work area using tabs and splitters.



## NumPy Tutorial: Data Analysis with Python
- NumPy is a commonly used Python data analysis packag.

## Lists Of Lists for CSV Data
Before using NumPy, we’ll first try to work with the data using Python and the csv package. We can read in the file using the csv.reader object, which will allow us to read in and split up all the content from the ssv file.

In the below code, we:

- Import the csv library.

- Open the winequality-red.csv file.

With the file open, create a new csv.reader object.

- Pass in the keyword argument delimiter=";" to make sure that the records are split up on the semicolon character instead of the default comma character.

- Call the list type to get all the rows from the file.

- Assign the result to wines.

## Creating A NumPy Array

- Import the numpy package.
- Pass the list of lists wines into the array function, which converts it into a NumPy array.
- Exclude the header row with list slicing.
- Specify the keyword argument dtype to make sure each element is converted to a float. We’ll dive more into what the dtype is later on.

