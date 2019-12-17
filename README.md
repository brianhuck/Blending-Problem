# Integer-Programming-Blending-Problem
I solve a blending problem, which is commonly discussed in Ops Research literature, using google's 'ortools' package in Python

My goal with this problem is to solve a somewhat complex problem.  The problem requires multiple variables with subscripts as well as the use of tables to organize the assumptions. 

This practice problem is preseted in the book, 'Ops Research: Applications and Algorithms 3rd ed,' by Wayne L. Winston on page 85

PROBLEM

An oil company creates three types of gas (gas1, gas2, and gas3).  Each type is
produced by blending three types of crude oil (crude1, crude2, and crude3).  

        purchase price    octance rating    sulfure content   
        ($/barrel)     
crude1  45                12                 0.5 %
crude2  35                6                  2.0 %
crude3  25                8                  3.0 %

      sales price ($/barrel)
gas1  70
gas2  60 
gas3  50 

The company can purchase 5,000 barrels of crude oil per day

Gas1: must have an average octane rating of at least 10 and contain at most 1% sulfur 
Gas2: must have an average octane rating of at least 8 and contain at most 2% sulfur
Gas3: must have an average octane rating of at least 6 and contain at most 1% sulfur

It costs $ 4 to transform one barrel of oil into one barrel of gasoline and the companies
refinery can produce up to 14,000 barrels of gasoline daily.

Customers require the following amounts of each gasoline:
gas1 - 3,000 barrels per day
gas2 - 2,000 barrels per day
gas3 - 1,000 barrels per day

Each dollar spent on advertising for a certain gas increases the demand by 10 barrels per day

Maximize daily profits (profits = revenue - costs)
