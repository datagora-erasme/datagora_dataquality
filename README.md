# datagora_dataquality

## Project description
This project aims to develop a versatile tool to measure data quality and automatically improve data sets.
In this project, the data quality analysis functions are:

+ empty cell detection
+ duplicate detection
+ detection of special characters
+ detection of outliers

A copy of the original dataset can be created without duplicates, outliers, or special characters.

A second tool allows the user to identify geographic data that is not in the metropolis of Lyon.

The third tool is a version management tool, comparing two versions of the same data set.

These three tools can be used with Excel or JSON files, new formats can be added later

A complete description of these functionalities is available in French in the file "User documentation.docx".

## How to use it ?

**Only works on Windows** 


<code> 
pip install django xlrd openpyxl pywin32 matplotlib shapely
sudo apt-get install python3-tk
cd mysite
python manage.py runserver
</code>

