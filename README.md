# stock-analysis


## Overview of Project
### Purpose 
The purpose of this project is to refactor as script that was used analyze stock market data in 2017/2018 and see the results as well as differences between the two different years. There are 12 different stocks within the data source which have data from 2017 and 2018. With a click of the button "Run Analysis for All Stocks" , within the "All Stocks Analysis" sheet, total daily volume and return are calculated based on the year chosen (2017/2018). After recfacotring the original script, the advantages and disadvantages are reflected on in general and to this specific VBA project.

## Results

### Comparing the stocks performances between 2017 and 2018
Below are the outputs for 2017 and 2018 after pressing the "Run Analysis for All Stocks" button and choosing desired year.


![image](https://user-images.githubusercontent.com/96553992/149435889-53e1175f-f914-4cf9-ab02-b3dbe666d6c1.png)

<img width="457" alt="VBA_Challenge_2018" src="https://user-images.githubusercontent.com/96553992/149584160-aca6108c-a0a0-4c64-8361-7061f551c109.png">

In general, the stock provided better return in 2017 compared to 2018. In 2017, all stocks but "TERP" stock had positive return. While in 2018, only "RUN" and "ENPH" stock had positive return while the rest were negative. As for total daily volume, 2017 had total average of 263,886,592 and 2018 had total average of 275,503,183. As a whole, more stock was traded on average for the year of 2018. # add more about analysis??

### Execution times between original and refactored script

The execution time for the refactored macro code ran faster than the original macro code. On average the execution for the orginal code took 0.30 seconds to run the macro for both 2017 and 2018. The refactored macro took about .08 second on average to run the macro for both years. This was due to merging of the two macros in the refactored code as well as adding a ticker index to loop through the stock data quicker. 



##Summary

### Advantages of refactoring code 

The advantages of refactoring code is having the code run quicker and smoother. Another advantage is to clean up and identify ways to use less lines of code to bring the same exact output. Refactoring code can also aid in reducing complexity so that another programmer or stakeholder has an easier time understanding what pieces of code are doing within a script. The quality of the code increases which leads to saving time and money while also making it easier to read and edit code in the future.
### Disadvantages of refactoring code 
One of the big disadvantages of refactoring code is the amount of time that it takes to factor the code. There is not exact timeframe in how long it will take to imporve the quality of the code. If you are time constrained to meet a deadline or complete a piece of code, you may not have time to refactor the code becasue it already works. When dealing with bigger code or programs, it can be risky to refactor code because of complex design and the resources it would take to refactor the code. Sometimes refacorting code is not the best option if you want to save time and money.

### Pros and Cons of refactoring the original All Stocks Analysis VBA script 

The pros of refactoring the original "All Stocks Analysis" script was the amount of time that was saved. The refactored script ran 0.22 seconds faster on average the the origincal script. Another pro was the readability of the script after refactoring it. Someone seeing my code for the first time could interpret what my code with ease and follow along to how I got to the final product. On the other hand, a con of refactoring the "All Stocks Analysis" script was the additional time that was spent improving the quality of the code. This extra time could have been spent adding different features to the code. 

