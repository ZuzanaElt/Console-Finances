# Console-Finances
challenge week 4

This challenge consists of a number of tasks
- create let totalNumberMonths 
    - this was completed using the .length of array function

- calculate net total amount of Profit or Loses over totalNumberMonths and then averaging
    - completed by first adding all the profit/lossed using for () loop and then dividing the result value byi number of months 

- finding the highest and the lowest profit/loss with months and specifying which ones they are
    -this proved difficult:
    1. I first tried to create a separate array and using 
        -e.g.let greatestIncrease = Math.max(...newArray); I found the highest and the lowest values.
    but these values were no longer connected to their months
    2. I then attached the calculated differences using .push to the existing finances array which is bringing me into multidimentional arrays area.
   ( see image in image folder)

    3. i couldnt figure out how to pick the highest value from the joined pushed into array so I decided to create a newArray with only lowest/highest profit and find the information this way
        let greatestIncrease = Math.max(...newArray);
        let greatestDecrease= Math.min(...newArray);
    4. 



- the highest value of profit with date  and amount 
    Greatest Increase in Profits: Feb-2012 (with corresponding amount of the month of the correct month)
- the largest decrease in losses 
    "Greatest Decrease in Profits: Sep-2013 ($-2196167)"