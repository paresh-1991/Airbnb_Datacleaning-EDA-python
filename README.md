# Airbnb_Data-cleaning-python-project
The goal of this notebook is to clean the raw airbnb Amsterdam dataset. The dataset can be found here:http://insideairbnb.com/get-the-data.html.
NB:( i do not own any rights on this dataset).
##Cleaning Data


The focus of this notebook is on cleaning the data and storing the cleaned version.  The strategy employed for cleaning the data is as follows:
- Drop columns that are not relevant to the problem. Example: URL, host picture etc.
- Find missing values for each column.
- Drop columns which have more than 20% missing data. Make a note of the columns.
- Convert columns to their correct data type.
- Subset the dataset based on certain criterion. Ex: property_type = Apartment/House/Townhouse/Condo
- Treating Missing values.
- Processing columns "PRICE" and "bathroom_texts" into proper output.
- Handling Outliers
- feature Engineering: changing amenties text column to bag of words representing each amentity
