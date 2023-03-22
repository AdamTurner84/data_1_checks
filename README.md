# data_1_checks
The Repo is to store all Adam Turner's CodeLouisville Knowledge Checks.

#Final Project Notes -- 

Final Project files -- 
The main project coding file is called friut_veg_final.ipynb. Additional files that are needed for the code to run are cust_data.csv, order_data.csv, and prod_data.xlsx and these files are stored in the folder titled final_files.

Project Description -- 
For this project I created a sales data set. The goal is that a Fruit and Veggie sales company wants to know their top most profitable customers and their most profitable regions of sales. Their data is currently being stored in three different files. Two of the files are saved in .csv format and one is stored in .xslx format. My goal is to create code that will import the data into Python and set up one master file. Once the data has been stored in a master file it will need to be cleaned (removing NaN values, selecting only the columns needed, and making sure data types are correct.) After the cleaning of the data the code will analyze the sales figures to locate the top 15 most profitable customers and the most profitable region. I will also make graphs that will give a pictoral representation of this data.

Relavant Packages -- 
This code was created in Visual Studio Code with Jupyter Notebooks. Jupyter notebooks will need to be installed on the IDE you are working with. To run this code you will need to install the latest version of Python and the packages Pandas, Numpy and Matplotlib. These packages can be installed by going to the command prompt (PC) Terminal (Mac) and run:

pip3 install pandas
pip3 install numpy
pip3 install matplotlib

Features -- 
1. Reading the data into Python from .csv and .xlsx files. 
2. Cleaning the data including removing unwanted columns, changing the data types of columns, and replacing NaN values with correct data. 
3. Analysing data to identify the 15 most profitable customers and list teh sales regions by most profitable.
4. Take the data sets from point 3 and graphed those to have a visual representation of the data. 
5. Markdown sections have been listed between each codeblock to give details on what the code is doing.

Data Sets -- 
I created the data sets that are being used in this project. There were three main files: one for customer data, one for product data, and one for sales data. This data needed to concatenated and orgainzed to really be usable for analysis. One of the benefits of this code is that as the company adds more information (Customers, Products and Sales) to their main files. This code can be run again and will generate updated results based on the updated data. 
