# JSONBWORLDBANKPROJECT - The Goal is to explore and manipulate data extracted via a JSON storage file

Find the 10 countries with the most projects.  

Find the top 10 major project themes (using column mjtheme_namecode). 

For some entries in the exercise above, the name is missing. Create a dataframe filling in the missing names.   

Import Packages, Load JSON file as a Dataframe, Inspect - Get a look at the state and structure of the dataset. 

Inspect the columns needed for the exercises. 

Find the 10 Countries with the Most Projects - 

Retrieve a value count of country names, which is sorted in descending order; save the first 10 results.

Load JSON file as a String, Flatten, Inspect - The column needed to finish the exercises contains nested data, 
so it needs to be normalized. 

Find the Top 10 Major Project Themes - 
This is accomplished by a value count of project codes since names are known to be missing.  
Create a Dataframe Filling in the Missing Names - 
Sort the dataframe, fill empty cells with NULL values, then replace those by backfilling.  
Find the Top 10 Major Project Themes by Theme Name - 
Produce a more descriptive list of top projects by getting a value count of project names.
