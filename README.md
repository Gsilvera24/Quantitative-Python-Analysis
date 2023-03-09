Financial Analysis using Python
======

Python script that analyzes financial records to calculate each of the following:

* The total number of months included in the dataset.
* The net total amount of Profit/Losses over the entire period.
* The average of the changes in Profit/Losses over the entire period.
* The greatest increase in profits (date and amount) over the entire period.
* The greatest decrease in losses (date and amount) over the entire period.

Specificially, the financial records is a .csv file containing budget data over several years.

Procedure & Screenshots
======

The following is a screenshot of my notebook file rendered in VS Code where I have imported the Pandas and Path libraries. 
After, I simply pointed my path variable to a CSV file named "budget_data" and loaded the dataframe using the .read_csv function.
 
 
![alt text](https://github.com/Gsilvera24/Simple-Python-Analysis/blob/main/images/financial_one.png "VS CODE")

Next, I calculated the total number of months, net profit/losses, and net change over the entire period.

![alt text](https://github.com/Gsilvera24/Simple-Python-Analysis/blob/main/images/financial_three.png "VS CODE")

Finally , I calculated the average change, maximum change, and minimum change of budget over the entired period.

![alt text](https://github.com/Gsilvera24/Simple-Python-Analysis/blob/main/images/financial_four.png "VS CODE")


That's at! Overall, this is a simple overview of budget data. Some months budget was negative and some months positive. This analysis paints a better picture of what happened with the amounts over time. Feel free to use this code if you have similar data!
