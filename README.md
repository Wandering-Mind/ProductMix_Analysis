
USING THE FILE “PRODUCTMIX_ASSIGNMENT.XLSX”, COMPLETE THE FOLLOWING:  
  Objective: To use Solver (Linear Programming) to find a mix of computer models that maximizes total net profit 
  and stays within the labor hour availability and maximum sales constraints. PC Tech now has eight available 
  models, not just two, and there are now two lines for testing. 

    a. The first line tends to test faster, but its labor costs are slightly higher, and each line has a certain 
number of hours available for testing. 
    b. PC Tech must decide not only how many of each model to produce, but also how many of each 
model to test on each line. 
    c. The table below lists the variables and constraints for this model.  
Type & Description

Decision Variables (changing cells) = Number of computers of each model to test on each of the lines (line 1, line 2) 
Objective Cell = Total Net Profit  
Constraints (11 total for Solver) = Computers produced cannot equal or exceed the maximum sales for each model. Labor Hours Used cannot exceed the Labor Hours Available. 
Other Calculations = See below for instructions/step-by-step 
1. Orange Cells (rows 14, 15): Calculate the Unit Margins on Rows 14 and 15 for each Model using the 
given information. The Unit Margin is the Selling Price – Labor and Assembly Costs 
  a. Note: You are calculating the testing lines separately because each has a different $ 
  associated. In Row 14, you will calculate the following for each of the 8 models: 
  Selling Price – Cost per labor hour assembling*Labor hours for assembly - Cost per labor hour 
  testing, line 1* Labor hours for testing, line 1 - Cost of component parts 
  For Row 15, it is the same but you will switch out the Cost per labor hour testing, line 1* Labor 
  hours for testing, line 1 for line 2 for all 8 models.  

2. Purple Cells (row 21): Calculate the total number of computers produced by taking the sum of the 
number tested on line 1 and number tested on line 2 for each of the cells in row 21.  

3. Red Cells: As a note for you before clicking Solver, place the comparison operator for each (<=, >=, <, 
>). This should reflect that the Total computers produced for each of the 8 models cannot equal or 
exceed the amount provided in Row 23 for Maximum Sales. This will be a constraint that you build into 
Solver. Do the same for the labor constraint (red cells). 

4. Tan cells (B26:B28): Calculate the total Labor by using the following formulas: 
  a. B26 = SUMPRODUCT(B9:I9, B21:I21)  
  b. B27 = SUMPRODUCT(B10:I10, B19:I19)  
  c. B28 = SUMPRODUCT(B11:I11, B20:I20)  

5. Aqua cells (Rows 31, 32): Calculate the Net Profit by taking the Unit Margin, tested on line 1*Number 
tested on line 1 for each of the 8 models in row 31, B:I. Do the same for tested on line 2 in Row 32 for 
B:I.  
6. Green Cells (J31:J33): Sum the totals for row 31 and 32. In cell, J33, sum the totals.**
