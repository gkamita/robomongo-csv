# robomongo-csv
Improved csv output script for mongoDB client Robo 3T

The origian script from https://github.com/Studio3T/robomongo/wiki/How-to-export-to-CSV, outputs the csv with all values in quotes, e.g. "string-value", "1.23". This can be a problem for reusing the data in other programs such as python, because python inferes the datatype by the presence/absence of quotes. This script removes the quotes from numbers and the header, so that the exported csv becomes ready to be loaded in python. For usage, follow instructions in the above link.
