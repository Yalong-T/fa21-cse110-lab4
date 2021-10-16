1. print 3. The variable 'i' is var type, so even though its only defined in each iteration of for loop, its still can be accessed  after for loop. The length of prices is 3, so i = 3.
2. Print 150. The variable 'discountedPrice' is var type, so even though its only defined in each iteration of for loop, its still can be accessed  after for loop. When i=2, discountedPrice = 300 * 0.5 = 150
3. Print 150. we declared finalPrice inside of function, every time the for loop will update the finalPrice result. The last time should be 150*100/100 = 150.
4. Result: [ 50, 100, 150 ]. Push each iteration finalPrice result into discounted array. Finally, we return discounted array.
5. Error. i is not defined out of for loop. We can not accessed it after for loop.
6. Error. discountedPrice is not defined out of for loop. We can not accessed it after for loop.
7. Print 150 at line 14. We define variable finalPrice before in this function, so we can access it in this function.
8. It will return [ 50, 100, 150 ]. Push each iteration finalPrice result into discounted array. Finally, we return discounted array. all variables are defined correctly.
9. error. i is not defined out of for loop. We can not accessed it after for loop
10. Print 3. The length of list prices is 3, and we assign prices's length to length variable.
11. It will return [ 50, 100, 150 ]. In for loop, we push each discountedPrice result to our list discounted. This is valid because we did not reassign or redeclare variable discounted.
12. A. student.name B. student['Grad Year']; C. student.greeting(); D. student['Favorite Teacher'].name; E. student.courseLoad[0]
13. Arithmetic
<ol type="A">
  <li>Answer is '32'. Since this is '+' symbol, Javascript will  treats command as a string concatenation</li>
  <li>Answer is 1. Since this is '-' symbol, it cannot be operator for string. Convert string to number then does arithmetic subtraction</li>
  <li>Answer is 3. Null will be convert to numerically 0. 0+3=3</li>
  <li>Answer is '3null'. Since '3' is string, then + with null. Null will convert to string 'null' then apply string concatenation</li> 
  <li>Answer is 4. true will convert to 1, then add with 3</li> 
  <li>Answer is 0. false maps to 0, and null maps to 0. Therefore, the result is 0</li> 
  <li>Answer is '3undefined'. '3' is string with + symbol, apply string concatenation convert undefined to string.</li> 
  <li>Answer is NaN. Since the operator is '-' means we need convert 3 to number, but the undefined cannot convert to number. Thus, the result is NaN</li> 
</ol>

14. Comparison
<ol type="A">
  <li>true. convert string '2' to number 2</li>
  <li>false. These are 2 strings comparison, in lexicographical order in ASCii code '2' is greater than '1'  </li>
  <li>true. compare with integer 2, string '2' will be convert to integer. 2 is equal to 2</li>
  <li>false. the === will compare the type. 2 is integer, but '2' is string. They are different types.</li> 
  <li>false. true is 1, 1 not equal to 2. Thus, return false</li> 
  <li>true. Boolean(2) will return true, and compare with true. They are same type and same value.</li> 
</ol>

15.  The == operation can make type convert if 2 arguments are different types. However, === cannot do type convert, which means it will compare value and type.
16.  Code save in part2-question16.js
17.  The result will be [2, 4, 6] because in line 3 for loop we use callback function to pass each element in array to doSomething function and return element*2, and push it to newArr. 
18.  Answer save in part2-question18.js
19.  The output is : <br>
1<br>
4<br>
3<br>
2<br>



  