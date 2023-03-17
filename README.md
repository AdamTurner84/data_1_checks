# data_1_checks
The Repo is to store all Adam Turner's CodeLouisville Knowledge Checks.

#Final Project Notes -- 

Final Project files -- friut_veg_final.ipynb, cust_data.csv, order_data.csv, and prod_data.xlsx are the files needed for this project.

Project Description -- For this project I created the data set. The idea is that a Fruit and Veggie sales company wants to know their top most profitable customers and their most profitable regions of sales. Their data is currently being stored in three files. Two of the files are saved in .csv format and one is stored in .xslx format. My goal is to create code that will import the data into Python and set up one master file. Once the data has been stored in a master file it will need to be cleaned (removing NaN values, selecting only the columns needed, and making sure data types are correct.) After the cleaning of the data the code will analyze the sales figures to locate the top 15 most profitable customers and the most profitable region. I will also make graphs that will give a pictoral representation of this data.

Relavant Packages -- To run this code you will need to install Pandas, Numpy and Matplotlib. These can be installed going to the command prompt and using pip install pandas, pip install numpy, and pip install matplotlib.

Features -- 1. Reading the data into Python from .csv and .xlsx files. 2. Cleaning the data including removing unwanted columns, chaning the data types of columns, and replacing NaN values with correct data. 3/4. In this project the customer wants the top 15 most profitable customers and to know which region is most profitable. I have added code that calculates and creates a new column for profit based on the existing data. Then the profits are analized by customer and region to see who is most profitable. Lastly a graph was created to give a pictoral image of this data. 5. Markdown sections have been listed between each codeblock to give details on what the code is doing.

Data Sets -- I created the data sets that are being used in this project. There were three main files: one for customer data, one for product data, and one for sales data. This data needed to concatenated and orgainzed to really be usable for analysis. After cimpleting the project I identifie additional data that would be helpful for the customer to maintain. Like: profit on all sales, full name of customers, etc. The files are stored in the final_files folder and the master file that is created gets saved here as well.
