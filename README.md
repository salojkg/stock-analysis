# Stock-Analysis- VBA Refactoring
## Overview of the Project
We are helping Steve to analyze the performance of Stocks for the two years to make decision regarding diversifying Investments of his parents. We have already created a solution for his requirements. The objective of this project is to optimize the code for enhancing the performance of the current solution.
## Results
We have achieved more than 80% performance improvement through refactoring the code. The below mention table illustrates the efficiency in runtime.

<img src="/resources/Refactoring.png"/>


## Summary
Refactoring is a really good weapon to maintain the code. 
### Pros
- Refactoring helps in  performance improvement.
- Refactoring makes Software easier to understand.

### Cons
- When the code base is big Refactoring is expensive & Time consuming.
- It will be hard to test the new changes without  proper Test Cases.


In this Project we have acheived the significant improvement in the performance by reducing the number of times the data rows are scanned. In the intial code base we were looping through all the rows in the data sheets 12 times for each ticker value. After refactoring we are only iterating through the rows once and using array to store all the results.As said the runtime memory useage is higher since we are using arrays compare to reusing the same variable in the old code.
