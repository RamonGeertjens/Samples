#Import Departments
##Overview

This simple script creates Samanage departments based on a CSV source.

##How to use
Edit import_departments.rb by adding your Samanage API credentials to the "email" and "pass" variables, then enter the following command:
`
ruby import_departments.rb filename.csv
`
This will create each department and generate a log entry for any errors that occur.