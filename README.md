# PYTHON GUIDE #3
# NumPy
NumPy (Numerical Python) is a Python library that focuses on scientific computing. NumPy Array has the ability to form N-dimensional array objects, which are similar to lists in Python.
### 1. Import NumPy
![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/334c8511-e1a5-4356-80d0-4e8760036b4a)
### 2. Check Version 
![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/6b438a33-606f-4b86-adad-9d9cf0644e0e)
### 3. Creating Arrays
![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/5771e546-6d03-4c48-a595-24d4aa934a63)
### 4. Data Types
![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/327d14bb-8458-4ec9-b35d-b7f13f5429a9)
### 5. Dimension on Numpy Array
A dimension in arrays is one level of array depth (nested arrays).
  - 0-D Arrays

    0-D arrays, or Scalars, are the elements in an array. Each value in an array is a 0-D array.
    
    ![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/544bffd5-ef11-4963-8afd-479b9a5457a2)

  - 1-D Arrays

    An array that has 0-D arrays as its elements is called uni-dimensional or 1-D array. These are the most common and basic arrays.

    ![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/0c6744bd-f632-4013-af7c-7b9f888553e6)


  - 2-D Arrays

    An array that has 1-D arrays as its elements is called a 2-D array. These are often used to represent matrix or 2nd order tensors.

    ![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/eb8ec569-2af0-4f83-83b5-f1d6650e1ab7)
    
    
  - 3-D Arrays
    
    An array that has 2-D arrays (matrices) as its elements is called 3-D array. These are often used to represent a 3rd order tensor.

    ![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/795af2d4-0f08-405c-89f8-87d111e82c53)

### 6. Check how many dimension on NumPy Arrays
![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/68434418-cd30-491d-8e36-c41aac05f902)


# Pandas
Pandas is a library in Python that provides easy-to-use data structures and data analysis. Pandas is commonly used to create tables, change data dimensions, check data, and so on. The basic data structure in Pandas is called DataFrame, which makes it easy for us to read a file with many types of formats such as .txt, .csv, and .tsv files.

### 1. Import Pandas
![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/67d6fe6d-77f4-437d-9754-af5ee4254ea6)
### 2. Data Series
Pandas Series is a one-dimensional labeled array capable of holding data of any type (integer, string, float, python objects, etc.).
- Object series has one data dimension.
- It doesn't have a column name because it only has one column.
- And it has an index.

![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/cd26456d-087b-41d7-a1c9-16f37b17be11)

a) Converting data into series

![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/df21bb7c-fcc4-4e5f-bfaa-c8758208ca86)

b) Convert from series to arrays

![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/6fdea7f9-58e9-4019-8f02-77287efc9a50)

c) Displays Index

The index is in the form of a range, where the start point is inclusive of the range and the stop point is exclusive of the range.

![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/72abe117-606a-4146-a998-5ab991534d89)

d) Calling explicit and implicit index data

![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/a3a5b68b-d4fe-4e4a-9195-53a58c6e32a7)

- This is data selection.
- Even though we have created an explicit index, we can still call the implicit index

![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/4037e933-51e8-4025-9129-b9944a3a99b4)

### 3. Loc and Iloc
Loc (Location):
- loc is used to access data based on labels or index names (explicit index)
- This allows you to access rows or columns based on the index name you want

 ![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/a7a1af25-3910-4e2c-8a9f-d7d12f46c6d5)

Iloc (Integer Location) :
- iloc is used to access data by position or integer index (implicit index)
- This allows you to access rows or columns based on numeric position

![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/73c16190-cf4e-4c4e-b7af-ef16b03bba72)

### 4. DataFrame
A Pandas DataFrame is a 2 dimensional data structure, like a 2 dimensional array, or a table with rows and columns.
- Load data csv
  
  The pandas function read_csv() reads in values, where the delimiter is a comma character.

  ![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/6859881b-1e3f-4a8c-8c63-8b27b480c561)

- head() method
  
  This function returns the first n rows for the object based on position. It is useful for quickly testing if your object has the right type of data in it.

  ![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/fd539abc-9bc1-4212-8824-82ace62c4ab2)

- tail() method

  The tail() method returns a specified number of last rows.

  ![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/25bf58d1-1f85-4863-a7c8-b85d48929440)

- info() method

  The info() method prints information about the DataFrame.
  The information contains the number of columns, column labels, column data types, memory usage, range index, and the number of cells in each column (non-null values).

  ![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/56b0f105-5a29-481c-9c86-fda4fb65a2f8)

- notnull() method
  
  The notnull() method returns a DataFrame object where all the values are replaced with a Boolean value True for NOT NULL values, and otherwise False.

- isnull() method

  The isnull() method returns a DataFrame object where all the values are replaced with a Boolean value True for NULL values, and otherwise False.

- sum() method

  The sum() method adds all values in each column and returns the sum for each column.

  ![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/07457dc8-8379-4661-9464-883773387f24)

- shape property

  The shape property returns a tuple containing the shape of the DataFrame. The shape is the number of rows and columns of the DataFrame.

  ![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/e2726b4f-c2db-4f93-9ab5-222fb415f20e)

- columns property

  The columns property returns the label of each column in the DataFrame.
  
  ![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/ff4711e4-683b-475b-a662-8c5233fa9d7c)

- index property

  The index property returns the index information of the DataFrame. The index information contains the labels of the rows. If the rows has NOT named indexes, the index property returns a RangeIndex object with the start, stop, and step values.

  ![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/6933661c-0405-4960-b7f2-a97bb34c9049)

- describe() method

  The describe() method returns description of the data in the DataFrame.

  ![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/45c9766c-3160-43d0-8d74-272470ff1caf)

- mean() method

  The mean() method returns a Series with the mean value of each column.

  ![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/4732ec2a-16c2-41d4-a87f-a2c6e61fdb94)

- median() method

  The median() method returns a Series with the median value of each column.
  
  ![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/9020faca-8730-4b89-84dc-eb85752b9d2a)

- mode() method

  The mode() method returns the mode value of each column.

  ![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/f718b74b-e4be-4e23-94d2-2735f1083d0e)

- min() method

  The min() method returns a Series with the minimum value of each column.

  ![image](https://github.com/NinysRevalyna/python_guide_3/assets/72516143/f1efb600-3376-4395-97c2-8c6e5236e94e)



  

  

  

  

  
  














