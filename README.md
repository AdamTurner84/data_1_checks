# data_1_checks
The Repo is to store all Adam Turner's CodeLouisville Knowledge Checks.

#Final Project Notes -- 

Final Project files -- 
The main project coding file is called friut_veg_final.ipynb. Additional files that are needed for the code to run are cust_data.csv, order_data.csv, and prod_data.xlsx and these files are stored in the folder titled final_files.

Project Description -- 
For this project I created a sales data set. The goal is that a Fruit and Veggie sales company wants to know their top most profitable customers and their most profitable regions of sales. Their data is currently being stored in three different files. Two of the files are saved in .csv format and one is stored in .xslx format. My goal is to create code that will import the data into Python and set up one master file. Once the data has been stored in a master file it will need to be cleaned. After the cleaning of the data the code will analyze the sales figures to locate the top customers, products and regdions as well as the low performing customers, products and regions.

The benefit of this code is that as the company adds more data into the data sets the code can be re-run and generate the updated reports with the date it was run, based on the updated data. The Fruit and Veg company now has lists of their top preformers and customers as well as lowest preformers. This can help them in deciding how and where to target marketing and promotions.

Relavant Packages -- 
This code was created in Visual Studio Code with Jupyter Notebooks. Jupyter notebooks will need to be installed on the IDE you are working with. To run this code you will need to install the latest version of Python and the packages Pandas, Numpy, Matplotlib and Seaborn. These packages can be installed by going to the command prompt (PC) Terminal (Mac) and run:

pip3 install pandas
pip3 install numpy
pip3 install matplotlib
pip3 install seaborn

Once the above packages have been installed open the Jupyter Notebook titled 'friut_veg_final.ipynb' and click 'Run All'.

Features -- 
Upon opening the code file fruit_veg_final.ipynb select 'Run All'. The code will run generating the report and automatically storing the excel in the "report files" folder for later use and review.

1. Reading the data into Python from .csv and .xlsx files. 
2. Cleaning the data including removing unwanted columns, changing the data types of columns, and replacing NaN values with correct data. 
3. Analysing data to identify the 15 most profitable customers, 15 most profitable products and list the sales regions by most profitable.
4. Take the Top Customers and Regions data sets from point 3 and graph those to have a visual representation of the data. 
5. Analysng the data to indentify the lowest performing customers and products.

Data Sets -- 

Main coding file -- fruit_veg_final.ipynb
Needed files -- cust_data.csv, order_data.csv, and prod_data.xlsx
Files created by the code -- comp_data.csv (stored in 'final_files' folder). 
Files created by the code -- 'currentdate'_top_15_custs.png, 'currentdate'_regions_by_profit.png, 'current_date'_topreport.xlsx (stored in 'report_files' folder.)
