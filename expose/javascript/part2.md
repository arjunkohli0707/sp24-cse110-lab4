1) Line 12 prints `3` because the final value of i after the for loop is finished running is 3.
2) Line 13 prints `150` because in the last iteration of the for loop, discountedPrice is updated to become `prices[2]*(1- discount)` which is 300*0.5 = 150
3) 150 would be printed out again because finalPrice takes the value of discountedPrice in the last iteration of the for loop.
4) This function will return `[50, 100, 150]` as it essentially applies a 50% discount to the price of each item in the list prices.
5) The code will cause an error. Since the let keyword is used to create the variable i, it is not defined outside the scope of the for loop so when `console.log(i)` is run in line 12 there is an error since i is not defined.
6) The code will cause an error. Since the let keyword is used to create the variable discountedPrice, it is not defined outside the scope of the for loop so when `console.log(discountedPrice)` is run in line 13 there is an error since discountedPrice is not defined.
7) 150 would be printed out because finalPrice takes the value of discountedPrice in the last iteration of the for loop which is `prices[2]*(1- discount)` which is 300*0.5 = 150. This is because finalPrice is defined in the same block scope as the console.loh(finalPrice) statement.
8) 
