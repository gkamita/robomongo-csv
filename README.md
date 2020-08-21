# robomongo-csv
Improved csv output script for mongoDB client Robo 3T

The original script from https://github.com/Studio3T/robomongo/wiki/How-to-export-to-CSV, outputs csv with all values in quotes, e.g. "string-value", "1.23". This can be a problem for reusing the data in other programs such as Python, because Python infers the datatype by the presence/absence of quotes. This script removes the quotes from numbers and the header, so that the exported csv becomes ready to be loaded in Python. For usage, follow instructions in the above link.
