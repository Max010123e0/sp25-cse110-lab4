1. values added: 20
2. final result: 20
3. Notice that "var" cannot be block- or loop-local. Here, "var" is a function-level variable. This caused sumValues function to print both line 9 and line 13, since result is still stored even if the "if" statement block ended, which is not a purpose of sumValues function
4. values added: 20
5. It returned error. This is because "let" declaration is only visible inside the block. Therefore, since result is not defined on line 13, it threw the error.
6. It returned an error. Since const declaration prevents reassigning, it throws an error when trying to print out const variable that was attempted to be reassigned.
7. I threw an error as well, and same logic, it is due to reassign of const variable.
