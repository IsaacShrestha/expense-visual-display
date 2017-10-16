# expense-visual-display-V1
Expense visual display V1 is developed to help you track your personal expense and display it in form of human understandable charts. This is a small web-app. It loads data via CSV file and displays in the form of chart. At present it has one pie-chart displaying 'What did I spend for?', bar-chart displaying 'My expenditure detail' and second bar-chart displaying 'How much did I spend?'. The x-axis of 'How much did I spend?' bar-chart gives the frequency and bars give the amount spent.

It needs to be hosted either in Online server or localhost to enable it display charts according to data provided in CSV file. 
For V1, data needs to loaded manually into the CSV file as shown in table below:

| Timestamp        | Expenseid           | Expense-for  | Amount  | Category  |
| ---------------- |:-------------------:| ------------:|--------:| ---------:|
| 10/1/2017        | 1                   |  Rent        |   1600  |    Rent   | 
| 10/2/2017        | 2                   |  Subway      |   7     |    Food and grocery   | 


### Technology used: d3js, dcjs, crossfilter and datatable

### How to use it?
1. Download and install XAMPP or WAMP
2. Clone this repository in the hosting directory (i.e. www for wamp or htdocs for xampp)
3. Run it in browser
4. You can keep updating your expense in expense.csv file inside data-source directory


