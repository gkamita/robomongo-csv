# robomongo-csv
Improved csv output script for mongoDB client Robo 3T

The origian script from https://github.com/Studio3T/robomongo/wiki/How-to-export-to-CSV, outputs the csv with all valuesa including numbers in "". This can be aproblem for reusing the data in other programs such as python, because python inferes the datatype by the absence/presence of "". This script removes the ""s so that the exported csv becomes ready to be loaded in python.
