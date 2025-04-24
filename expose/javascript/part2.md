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
