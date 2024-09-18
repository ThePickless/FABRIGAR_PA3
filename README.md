# EXPERIMENT 3 - PYTHON DATA ANALYSIS

Repository #3 shows Python scripts designed to solve various problems in Advanced Programming. Below is a summary of each script. 

### Problem 1

##### This specific problem set requires you to access pandas from the library and loading a ".csv" file into your notebook and to answer the following questions:

**Function:**

```python

#access
import pandas pd 

#read and output the declared ".csv" file
cars = pd.read_csv('cars.csv')
cars

```

**Output:**

![image](https://github.com/user-attachments/assets/ed248319-09b2-47ca-a279-1b57c0b89473)

![image](https://github.com/user-attachments/assets/24b0aefc-da9f-40e5-be91-5f6c74a4a637)

##### First task is to load the first 5 rows of the given csv file above and to do so, you just need to input the following function:

**Function:**

```python

#load the first five rows from the ".csv" file
cars.head()

```

##### Second task is to load the last 5 rows of the given csv file and to do so, you need to input the following function:

**Function:**

```python

#load the last five rows from the ".csv" file
cars.tail()

```

**Output:**

![image](https://github.com/user-attachments/assets/8f219257-a6d5-45b2-9ea6-1c012cc0d31a)

### Problem 2

##### This problem set gives you a specific set of tasks using subsetting, slicing, and indexing to input what is particularly asked for, let's see the following questions:

**Function:**

```python

#outputs the first five rows from the csv file with odd numbered columns
odd = cars.iloc[:5,::2]
odd

```

**Output:**

![image](https://github.com/user-attachments/assets/bd20c80a-3876-4d93-a5f2-af7749979782)

**Function:**

```python

#outputs the row containing the model of Mazda RX4
cars.loc[[1]]

```

**Output:**

![image](https://github.com/user-attachments/assets/effa9fc6-ecdb-4b17-9282-b70d4b80c71e)

**Function:**

```python

#outputs the value for "cyl" of car model 'Camaro Z28'
cars.loc[[23],['cyl']]

```

**Output:**

![image](https://github.com/user-attachments/assets/2844e616-5786-4221-9f78-b909eb6fb215)

**Function:**

```python

#output the values for "cyl" and "gear" for the following car models
cars.loc[[1,18,28],['cyl','gear']]

```

**Output:**

![image](https://github.com/user-attachments/assets/fff50e04-3503-45e3-93b1-9d234ed48883)

### That is it for this repository I hope you learned something :)))
