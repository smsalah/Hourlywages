# Hourlywages
This repository contains an odoo module called hourlywages. This module adds a field hourlywage in the Employee Contract and calculate 
hourly salary hy using this field.

Here is how it works

1) The module adds a filed "hourlywage" in HR Contract.
2) It creates a salary rule "Hourly Salary" that calculates the total hourly salary using the following formula
result = contract.hourlywage * worked_days.WORK100.number_of_hours
worked_days.WORK100.number_of_hours are total number of hours
3) It also creates a  Salary structure called "Hourly Salary Structure" that uses above said rule to calculate hourly salary.
