1) The bug was that both num1 and num2 are of type string so when result is assigned to the sum of num1 and num2, it is the strings num1 and num2 concatenated
2) I fixed the bug inside calculateSum by type converting num1 and num2 to numbers using the Number() function and then adding these type converted nums to give result. The fix can be seen at ![img](../../expand/screenshots/fix.png)
