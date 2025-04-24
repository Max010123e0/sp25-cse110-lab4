1. It prints 3. It's because for loop iterated 3 times, due to a length of "prices" array
2. It prints 150. Notice that variable "discountedPrice" is reassigned on each iteration, therefore the discounted price of the last iteration, 150, should be stored and console.log prints its value
3. It prints 150. Notice that it is just round of discounted Price, which is still 150 from the last iteration. console.log still prints out 150 for this code as well.
4. It prints [50, 100, 150]. Since the function has "return discounted", which means returning discounted variable, it prints out the elements within the array, which are the discounted prices.
5. This causes an error since let declaration is visible only within the scope. Since line 12 is out of the for loop, it is not visible and it throws an error.
6. This Throws an error as well. Same logic, since line 13 is out of for loop scope, the variable is not visible and it throws an error.
7. It prints 150. Notice that the declaration of the finalPrice is within the funcion-scope, so it is still visible. It shows finalPrice of last iteration, so it prints 150.
8. This function returns array of discounted price, which was stored in "discounted"[50, 100, 150]. Since "discounted" used let declaration in the function-scope, it is till visible and the function returned the variable.
9. It throws an error, since scope of const declaration behaves same as let declaration. Since "I" was declared within for loop, line 11 cannot see the value of variable "I".
10. It orubts 3. Since declartion of length is in function-scope, line 12 can see its value so it prints length of the prices array, which is 3.
11. It returns an array of discounted price, which was stored in "discounted" variable: [50, 100, 150]. Notice that discounted variable is declared within the function scope, so it successfully returns the stored array.
12. 
 A. student.name
 B. student['Grad Year']
 C. student.greeting()
 D. student['Favorite Teacher'].name
 E. student.courseLoad[0]
13.
 A. 32, since integers map to their exact string representation
 B. 1, since '-' operation turns the string into integer, than doing the subtraction
 C. 3, since null converts to 0 in numeric operation
 D. 3null, since null is null in string operation
 E. 4, since '+' operation is used and true converts to 1 in numeric operation
 F. 0, since both false and null converts to 0 on numeric operation
 G. 3undefined, since '3' is string and undefined is undefined in string operation
 H. NaN, since '-' forces numeric conversion and operation, and undefined turns into NaN when numeric conversion -> 3 - NaN is NaN
14. 
 A. true, since comparison operators change string into numeric values when it is compared to integers, and 2 > 1 is true
 B. false, since they are both strings, and it is doing lexicographical order comparison
 C. true, since == operator converts string into numerica valuse when compared to integers
 D. false, '===' operator checks if they are same type.
 E. false, since true is coverted to 1, numeric value, and it is different to 2
 F. true, since Boolean(2) gives 'true', which is same type and value to the former value.
15. '==' operator converts one of the variables into the same type with the other variable, and it checks their equalty. Therefore, it can hold true when the values are same, even if their ty[es are different. However, '===' checks both value and types, which performs a more rigorous comparison.
16. 
