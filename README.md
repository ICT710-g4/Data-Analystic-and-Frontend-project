# Data-Analystics-and-Frontend-project

## Members

| Name | StudentID |
|--|--|
| Isada Sukprapa| 6222040302 |
| Narusorn Sirivon  | 6222040310 |
| Menghorng Bun | 6222040096 |


# Test Case
**Frontend-TC-001**\
**Description:**
Frontend page can issue POST request and recieve POST response from API server\
**Test Procedure:**
1. access the webpage
2. read and note the device status
3. send POST request for device status to API server via Postman
4. confirm the reading with the webpage
<a/>

**Test Data/Device:**
API POST response\
**Expected Result:**
Webpage have the same response as Postman method\

**DA01-load_csv**

**Description:** To load model from csv file, print out the description, return dataframe

**Procedures:**
1. Call load_csv function with parameter is test data
2. Observe the result

**Test data:**
- test_data1: 
	- paratemer: "data.csv"
	- detail: which file is exist and format correct
- test_data2: 
	- parameter: "data.csv"
	- detail: which file is not exist
- test_data3: 
	- parameter: "data.csv"
	- detail: which file exist but wrong format

**Expected results:**
- test_data1: print describtion and return DataFrame object
- test_data2: error
- test_data3: error

**DA02-plot_scatter**

**Description:** Plot the scatter graph for obeserve the data distribution

**Procedures:**
1. Call load_csv function with parameter is test data
2. Observe the result

**Test data:**
- test_data1:
	- parameter: "df"
	- detail: which df is DataFrame type object
- test_data2:
	- parameter: "df"
	- detail: which df is not DataFrame type object

**Expected results:**
- test_data1: plot scatter graph
- test_data2: error

**DA03-train_model**

**Description:** Train the selected model from data, and dump the model into file 

**Procedures:**
1. Call plot_scatter function with parameter is test data
2. Observe the result

**Test data:**
- test_data1: 
	- parameter: "df", "model_name"
	- detail: which df is DataFrame type object, "model_name" is exist
- test_data2:
	- parameter: "df", "model_name"
	- detail: which df is DataFrame type object, "model_name" is not exist
- test_data3:
	- parameter: "df", "model_name"
	- detail: which df isn't DataFrame type object, "model_name" is exist
- test_data4:
	- parameter: "df"
	- detail: which df is DataFrame type object, "model_name" is not declared

**Expected results:**
- test_data1: plot scatter graph
- test_data2: error
- test_data3: error
- test_data4: error

**Frontend interface**

Working on HTML CSS and Javascrip:

	-Read data from data analysis 
	
	-Display the stutus of each device
	
**for testing**

	Reading data by human input to replace data from data analysis
	
	Using button "start" to make situation refresh page.
	
	Display stutus. 
