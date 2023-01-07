# Console-Finances
challenge week 4

This challenge consists of a number of tasks
- create let totalNumberMonths 
    - this was completed using the .length of array function

- calculate net total amount of Profit or Loses over totalNumberMonths and then averaging
    - completed by first adding all the profit/losses using for() loop and then dividing the result value by i number of months 

- finding the highest and the lowest profit/loss with months and specifying which ones they are
    -this proved difficult:

    1. I first tried to create a separate array and using 
        -e.g.let greatestIncrease = Math.max(...newArray); I found the highest and the lowest values.
        but these values were no longer connected to their months

        2. I then attached the calculated differences using .push to the existing finances array which is bringing me into multidimentional arrays area.
        ( see image in image folder)![screenshot of calculating differences](images/Screenshot%20(24).png)

    3. I couldn't figure out how to pick the highest value from the joined pushed into array   so I decided to create a newArray with only lowest/highest profit and find the information this way
        let greatestIncrease = Math.max(...newArray);
        let greatestDecrease= Math.min(...newArray);

    4. From then on I could compare the the 2 arrays which allowed me to console.log them

   [screenshot of result](images/financial%20analysis%20result.png)

# Code to remember

- rounding number to 2 decimals : let averChange=Math.round((differBetMonths/(finances.length-1))*100)/100;
- pushing element to end of array: finances[0].push("0");
    push in for function:
    for (let i=0; i <totalNumberMonths; i++){
        finances[i].push(arrayCollectedDifferences[i]);}
- finding max an d mix in an array:
     let greatestIncrease = Math.max(...arrayCollectedDifferences);
 let greatestDecrease = Math.min(...arrayCollectedDifferences);

 
# Conclusion
I am sure I did not find the shortest and most beautiful code to solve this challenge, but I am happy that it works. It involved a lot of thinking and trying to find a working process how to approach logical challenges. 
The introduction to Java Script is tricky but I appreciate the pace which allows me to catch up at the end of the week.

URL to see the page and Console is:
https://zuzanaelt.github.io/Console-Finances/
Gihub page:
https://github.com/ZuzanaElt/Console-Finances