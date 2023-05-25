# RomanNumeralConverter

In the code snippet for (var i = 0; i < decimalValues.length; i++), a for loop is used to iterate over the decimalValues array, which contains the decimal values corresponding to Roman numerals. It initializes the loop variable i to 0, and the loop continues as long as i is less than the length of the decimalValues array. After each iteration of the loop, the loop variable i is incremented by 1.

Inside the loop, there is a while loop with the condition num >= decimalValues[i]. This while loop executes as long as the given num is greater than or equal to the current decimal value at index i. It is used to handle cases where the given number can be represented by multiple symbols of the same Roman numeral.

During each iteration of the while loop, the corresponding Roman symbol at index i is added to the romanNumeral string, and the value of num is decreased by the current decimal value at index i. This process continues until the condition num >= decimalValues[i] is no longer satisfied.

By using the for loop and while loop combination, the function builds the Roman numeral representation of the given number by finding the largest decimal value that fits into the number and appending the corresponding Roman symbol to the result string.
