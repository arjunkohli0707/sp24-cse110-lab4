1) Line 12 prints `3` because the final value of i after the for loop is finished running is 3.
2) Line 13 prints `150` because in the last iteration of the for loop, discountedPrice is updated to become `prices[2]*(1- discount)` which is 300*0.5 = 150
3) 150 would be printed out again because finalPrice takes the value of discountedPrice in the last iteration of the for loop.
4) This function will return `[50, 100, 150]` as it essentially applies a 50% discount to the price of each item in the list prices.
5) The code will cause an error. Since the let keyword is used to create the variable i, it is not defined outside the scope of the for loop so when `console.log(i)` is run in line 12 there is an error since i is not defined.
6) The code will cause an error. Since the let keyword is used to create the variable discountedPrice, it is not defined outside the scope of the for loop so when `console.log(discountedPrice)` is run in line 13 there is an error since discountedPrice is not defined.
7) 150 would be printed out because finalPrice takes the value of discountedPrice in the last iteration of the for loop which is `prices[2]*(1- discount)` which is 300*0.5 = 150. This is because finalPrice is defined in the same block scope as the console.loh(finalPrice) statement.
8) This function will return `[50, 100, 150]` as it essentially applies a 50% discount to the price of each item in the list prices. This is because even though the let keyword is used, when the discounted array is updated, it always happens within the for loop which is in the same scope as finalPrice and discountedPrice.
9) The code will cause an error. Since the let keyword is used to create the variable i, it is not defined outside the scope of the for loop so when `console.log(i)` is run there is an error since i is not defined.
10) 3 will be printed to the terminal. This is because length is a const variable and the console.log(length) statement is in the same block scope as the statement where length is defined. Also length is not updated anywhere so there is no error.
11) This function will return `[50, 100, 150]` as it essentially applies a 50% discount to the price of each item in the array prices. This is because even though the const keyword is used, when the discounted array is updated, it always happens within the for loop which is in the same scope as finalPrice and discountedPrice. Also, discounted is a const array, which is why even though we cannot reassign the variable, we can add and remove from it.
12A) `student.name`
- B) `student["Grad Year]`
- C) `student.greeting()`
- D) `student["favorite teacher"].name`
- E) `student.courseLoad[0]`

13A) '32', because due to weak typing in javascript, when 2 (an int) is added to '3' (a string), 2 is also converted to a string so it results in a concatenation of 2 strings.
- B) 1, because due to weak typing in javascript, when 2 (an int) is subtracted from '3' (a string), 3 is also converted to an int so it results in 3 - 2 = 1. This happens when there are non-numbers involved in subtraction
- C) 3, because null takes on the numerical value of 0
- D) '3null', because null is converted to a string 'null' and concatenated with '3'
- E) 4, because true takes on its numerical value of 1 and is added to 3
- F) 0, because false takes on the numerical value 0 and so does null
- G) '3undefined' because undefined is converted to a string 'undefined' and concatenated with '3'
- H) NaN because when javascript sees arithmetic being performed, it converts undefined into a numerical value however undefined cannot be converted to a number, so it becomes NaN and 3 - NaN gives NaN

14A) true, because when '2' is compared with 1, '2' is converted to a numeric value of 2 and 2 is indeed greater than 1
- B) false, as the first char '2' is greater than the first char '1'
- C) true, as '2' is converted numerically to 2
- D) false, since === checks the equality without type conversion and 2 and '2' are if different types
- E) false, as the numeric value of true is 1 and 1 is not equal to 2
- F) true, because since 2 is a non zero value, Boolean(2) evaluates to true

15) == compares the equality of two objects with type conversion (for example 2 == '2' would evaluate to true because '2' gets converted to 2. === is a strict equality check which compares equality without type conversion (so 2 === '2' evaluates to false)

16) The code is in part2-question16.js
17) The result will be [2, 4, 6] which is basically each element of the input array doubled. This is because inside the for loop, newArr is appended in each iteration with the corresponding element of array modified by doSomething. And doSomething doubles whatever argument it is provided.
18) The code is in part2-question18.js
19) The output of the code is:
```
1
4
3
2
```
