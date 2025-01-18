# MyExcel_Projects
 Here are the general steps taken to complete these projects:
 Note:I had to copy the raw data to a new sheet called the working sheet on the excel file.
 General Steps taken for all the EXCEL Projects
 1.Deleting duplicates
 2.Standardizing of data format
 3.Removing blank/null values
 4.Removing unwanted columns when necesarry
 5.Creation of pivot table
 FOR HEALTHCARE DATASET
 1.Deleting duplicates
 Using the following buttons on the ribbon 
  -data--remove duplicates(where 534 duplicates were removed)
  2.Standardizing the format for each column
    I noticed that the names on the name column were not written in a standard format so i had to use
    the function PROPER(text) to change the letters into a standard form
  3.I had to inspect each column to ascertain that all the columns have a consistent format.
  4.Created a column called "Age Range" using the IF function ie
    =IF(B2>50,"Old",IF(B2>=20,"Middle Age",IF(B2<20,"Adolescent","Invalid")
    Note:From this stage i had to create another sheet called the pivot table in which i had select
    -data--insert--pivot table
    Furtheremore i had to create a dashboard sheet in which i had to provide a copy of all my visualization
