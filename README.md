# Crowdfunding_ETL

————————————————————————
## TASK##
————————————————————————

        We were tasked with building an ETL pipeline using Python, Pandas, and Python dictionary methods to extract and transform a company’s crowdfunding data. After transforming and cleaning the data, we created four CSV files and used the CSV file data to create an ERD and a table schema in PostgeSQl.

The 4 data frames created are as follows:

Campaign.csv
Contacts.csv
Subcategory.csv
Category.csv

      The campaign data frame is comprised of information describing 1000 different crowdfunding campaigns. The information includes ‘company name’, ‘category’ (business type), ‘subcategory’, ‘launched date’, ‘end date’, ‘outcome’, ‘goal’, ‘country’, ‘pledged’, ‘backers count’, ‘currency’, ‘contact id’, and ‘cf id’

       The contacts data frame contains information regarding the contact information for each company in the campaign data frame above. The information in the data frame includes ‘contact id’, ‘first name’, ‘last name’, and ‘email address’.

       The category and subcategory data frames both simply contain the different category/subcategory ids and the category/subcategory of each business.

Lastly, we used all of this information and each of the four data frames to create an ERD (entity relationship diagram). The ERD was then used to create a fully functional database in PostgreSQL.

Contributors:
Joanna Gromek
Nathan Beathea-Martinez
