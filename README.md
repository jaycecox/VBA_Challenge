# ALL STOCK ANALYSIS 

**Purpose:**

To analyze the stock performances of a given set of stocks using the most efficient coding method. In essence, to develop a refactored code that has the potential to run through thousands of stocks.  The analysis will show how active a stock is by showing how often a stock is traded throughout the day by calculating the Total Daily Volume. The analysis will also show the yearly return of each stock by looking at its starting and ending prices for the year. 

**Results Refactored Code:**

Overall the stocks had a better return in 2017 than in 2018.  Except for ‘TERP’, all of the 2017 stocks had a positive return, which you can see below. However, in 2018 the only stocks to have a positive return was ‘ENPH’ and ‘RUN”.  This analysis shows then that the two best stocks to invest in were ‘ENPH’ and ‘RUN’ because they had growth both years.   
![2017 Stock Perf Screen Shot](https://user-images.githubusercontent.com/92542382/140671490-3293c951-e5ea-4a6b-969e-b3e24a832c95.png)

![2018 Stock Perf Screen Shot](https://user-images.githubusercontent.com/92542382/140671498-24ac1b4e-7b31-4e89-b983-7f1fe84277da.png)

The above tables were created in part with the following code.  The code was designed to loop through the 2017 and 2018 worksheets and then pull and add the daily volumes for each ticker. The second to last line of code shows how the ‘Return’ percentage was calculated. 

![Code](https://user-images.githubusercontent.com/92542382/140671536-e04bb13b-e72f-48e3-a222-dd2532c62c20.png)

‘ENPH’ also has a 274% year over year percent increase in daily volume of trades. 

‘RUN’ had a 188% year over year percent increase in daily volume of trades. 

![% Change ENPH_RUN](https://user-images.githubusercontent.com/92542382/140671566-a93d8399-0f7e-4f01-8203-129bbb2cdba3.png)

As you can see below, whereas 2018 has more trade volume overall for all the analyzed stocks, it still had a worse return of stock price than 2017. 

![2017 Total Volume](https://user-images.githubusercontent.com/92542382/140671626-88fa3416-bb76-4699-a710-db817b3b1185.png)

![2018 Total Volumem Screen Shot](https://user-images.githubusercontent.com/92542382/140671638-ad7aabef-078f-4642-8847-63c792547dde.png)

**Refactored Code Execution Times**

![2017 refactored time](https://user-images.githubusercontent.com/92542382/140672656-278cf8b9-a752-44be-98ae-2b4ee5d904a5.png)

![2018 refactored time](https://user-images.githubusercontent.com/92542382/140671789-722a7e16-e042-40e1-94e9-bc9e36fbfe2f.png)

**Original Code Execution Times**

![2017 Original time](https://user-images.githubusercontent.com/92542382/140671889-d13828ca-f08b-4378-940d-a29c0c302d51.png)

![2018 original time](https://user-images.githubusercontent.com/92542382/140671933-70dad6b5-4bd5-4358-bd6e-f903a9dfd65a.png)

**Execution Times**

As you can see above, the refactored times for 2017 and 2018 were faster than the times for the original code. 

**Summary**

The advantage of refactoring the code is not only will the code run faster, but it is easier to read and therefore easier to update in the future. The refactored code allows for a better understanding of the function of each line of code. However code refactoring can be time consuming, as you are trying to figure out a new way to perform the same function as the original code. Also, refactoring code can take multiple trials in order to test each change to the code. 

Figuring out the refactored loop did take a considerable more amount of time than writing the double loop. Refactoring the original code decreased the run time and thus increased the efficiency. This efficiency was attained but removing the double loop and refactoring the code for a single loop. Please refer below.

**Original Loop**

![Original Loop](https://user-images.githubusercontent.com/92542382/140672010-7ba7ade4-6dda-4381-ab56-ff09a41a1c1b.png)

**Refactored Loop**

![Refactored Loop](https://user-images.githubusercontent.com/92542382/140672031-f220c593-5e96-4ce1-9403-849926a064a0.png)

