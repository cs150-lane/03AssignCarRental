## CS150 Assignment 3

Car Rental Invoice Calculator

**Points:** 25

**This is an individual assignment.**

**Goals:**
- Loops (do-while and while) 
- Input validation
- Logical Operators
- Running sums

You have been asked by a car rental company to write a program to create invoices for customers.

Your program will ask the user for the following information:
- Today’s day of the week (0 for Sunday 1 for Monday, … ,  6 for Saturday).
-	The weekday (Monday – Friday) rate in dollars.  
-	The weekend (Saturday and Sunday) rate in dollars.  
-	The number of days the customer  will rent the car.

You will then output an invoice showing the day number, the cost for the car that day, and a running total of the cost for the car thus far as is shown below (user input is in **bold**). 

<pre>
***********************
 Car Rental Calculator
***********************
What is the day today (0 – Sunday ... 6 - Saturday)? <b>3</b>
What is the weekday rate? $<b>49.95</b>
What is the weekend rate? $<b>29.95</b>
How many days will you rent the car? <b>10</b>

***************Summary of Costs***************
Day 1: Daily Cost: $49.95 Total Cost: $49.95
Day 2: Daily Cost: $49.95 Total Cost: $99.90
Day 3: Daily Cost: $49.95 Total Cost: $149.85
Day 4: Daily Cost: $29.95 Total Cost: $179.80
Day 5: Daily Cost: $29.95 Total Cost: $209.75
Day 6: Daily Cost: $49.95 Total Cost: $259.70
Day 7: Daily Cost: $49.95 Total Cost: $309.65
Day 8: Daily Cost: $49.95 Total Cost: $359.60
Day 9: Daily Cost: $49.95 Total Cost: $409.55
Day 10: Daily Cost: $49.95 Total Cost: $459.50

Total Cost: $459.50

Press any key to close this window . . .

</pre>


Some things to note:
1.	All user input should be validated:
     - The day today must be a number between 0 and 6, inclusive, and you can assume that the user will enter an integer.  
     - The weekday rate, the weekend rate, and the number of days the car will be rented all must be strictly greater than 0.  You may assume that the user will enter an integer for the number of days the car will be rented, but you should not assume this for the weekday rate and the weekend rate.  
If the user enters an invalid number, the user should be prompted again until a valid number is enter. 

2.	All monetary amounts must be displayed to 2 decimal places.

3.	The positions of the days of the week, 0-6, Sunday-Saturday, must be const

4.	There must be no magic constants in your program.

5.	You must follow the coding standards presented in class and provided on the class website.


**Examples of input validation (user input in bold):**
<pre>
***********************
 Car Rental Calculator
***********************
What is the day today (0 - Sunday ... 6 - Saturday)? <b>-1</b>
What is the day today (0 - Sunday ... 6 - Saturday)? <b>7 </b>
What is the day today (0 - Sunday ... 6 - Saturday)? <b>6 </b>
What is the weekday rate? $<b>0</b>
What is the weekday rate? $<b>50</b>
What is the weekend rate? $<b>-10</b>
What is the weekend rate? $<b>25</b>
How many days will you rent the car? <b>0</b>
How many days will you rent the car? <b>10</b>

***************Summary of Costs***************
Day 1: Daily Cost: $25.00 Total Cost: $25.00
Day 2: Daily Cost: $25.00 Total Cost: $50.00
Day 3: Daily Cost: $50.00 Total Cost: $100.00
Day 4: Daily Cost: $50.00 Total Cost: $150.00
Day 5: Daily Cost: $50.00 Total Cost: $200.00
Day 6: Daily Cost: $50.00 Total Cost: $250.00
Day 7: Daily Cost: $50.00 Total Cost: $300.00
Day 8: Daily Cost: $25.00 Total Cost: $325.00
Day 9: Daily Cost: $25.00 Total Cost: $350.00
Day 10: Daily Cost: $50.00 Total Cost: $400.00

Total Cost: $400.00

Press any key to close this window . . 

</pre>  


**To complete this assignment you must submit the following:**

1.  **An electronic Solution of your program on GitHub**
     - You are to click on the Assign03 Link on Moodle to accept this assignment as we’ve done in lab. Once accepted, code up a complete solution to the above assignment specification. Your complete solution is to be pushed to GitHub no later than the date and time specified above for your specific section.
     - Pay attention to the example output above. Your program’s output must look exactly like the example output! The spacing and newlines in your output must match exactly.
     - Make sure that your program compiles and runs correctly with no errors and no warnings. If you get any errors, double check that you typed everything correctly. Be aware that C++ is case-sensitive.

2.  **An electronic copy of your program is to be placed on Moodle**

    - See Lab01 for producing a pdf of your complete program. Once you have produced the pdf of your program and named the pdf your <b>punetidAssign03</b>, drop the pdf in the Assign03 folder on Moodle. 
    - The pdf must be in the drop folder on Moodle by the time and day specified above. Anything submitted after that will be considered late.

> **Good luck! And remember, if you have any problems, come and see straight away. **
