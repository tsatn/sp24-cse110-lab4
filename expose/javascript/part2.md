1. What will happen at line 12 and why?
    The code will print the number 3. 
    
    Explanation: There is no error caused by this line because the var declaration of i ensures it is available within the entire function scope, including after the loop.

2. What will happen at line 13? 
    It will output 150 to the console.

    Explanation: This occurs because discountedPrice is declared with var and thus retains its value across all iterations of the loop within the function scope, including after the loop has finished.

3. What will happen at line 14 and why?
    It will output 150 to the console.

    Explanation: There is no error caused by this line. The var keyword properly scopes finalPrice to the entire function, allowing it to be accessible and correctly holding its last assigned value after the loop.

4. What will this function return?
    It returns array [50, 100, 150].

    Explanation: Each price in the input array is halved due to the 0.5 discount factor, and the results are directly returned in the discounted array.

5. What will happen at line 12 and why?
    It will cause a ReferenceError: i is not defined error.

    Explanation: 
    You'll get a "ReferenceError: i is not defined". The let declaration limits i's scope to the loop block, so it’s not recognized outside of it.

6. What will happen at line 13 and why?
    It will cause a ReferenceError due to an attempt to access discountedPrice outside of its block scope.

    Explanation: The error message would typically be "ReferenceError: discountedPrice is not defined".

7. What will happen at line 14 and why?
    It will cause a ReferenceError: finalPrice is not defined" will occur. 

    Explanation: finalPrice is blocked-scoped within the loop due to its let declaration, making it inaccessible outside.

8. What will this function return?
    It will return the array [50, 100, 150].
    
    Explanation: The function finds the discounted prices for each item, rounds them, and stores them in an array, which is then returned.

9. What will happen at line 11 and why?
    Line 11 attempts to log the variable i to the console outside the for loop. 
    
    Explanation: Since i is declared with let inside the for loop, its scope is limited to that block. As a result, trying to access i outside the loop, where it is not defined, will cause a ReferenceError.

10. What Will Happen at Line 12?
    Output: The console.log(length) statement will correctly print 3.
    
    Explanation: length is used here to store the size of the prices array, which is correctly recognized as 3. Since there's no modification to length and it’s scoped appropriately to be accessible at line 12, it logs this value without any errors.

11. What will this function return?
    The function discountPrices takes two parameters: prices, an array of numbers representing prices, and discount, a number representing the discount rate to be applied. It returns a new array containing discounted prices.
    
12.  
    A. student.name

    B. student['Grad Year']

    C. student.greeting()

    D. student['Favorite Teacher'].name

    E. student.courseLoad[0]

13.   
    '3' + 2
        Output: '32'

        Explanation: In JavaScript, when a string is involved in a + operation with a number, the number is converted to a string and concatenated. Therefore, '3' + 2 results in the string '32'.

    '3' - 2
        Output: 1

        Explanation: Here, JavaScript converts the string '3' into a number for the subtraction. The - operator is not used for string concatenation, so JavaScript tries to convert all operands into numbers. Here, '3' is successfully converted to 3, and 3 - 2 equals 1.

    3 + null
        Output: 3

        Explanation: In JavaScript, null is often converted to 0 in numeric contexts. Adding 3 + 0 yields 3.

    '3' + null
        Output: '3null'

        Explanation: Adding null to a string converts null to the string 'null'.

    true + 3
        Output: 4

        Explanation: In JavaScript, true is converted to 1 in numeric contexts. Thus, 1 + 3 equals 4.

    false + null
        Output: 0

        Explanation: Both false and null are treated as 0 in numeric operations. Thus, 0 + 0 equals 0.

    '3' + undefined
        Output: '3undefined'

        Explanation: When using the + operator with a string, undefined is converted to the string 'undefined'. Therefore, '3' + undefined results in '3undefined'.

    '3' - undefined
        Output: NaN

        Explanation: Subtracting undefined from any number, including when it's derived from a string, results in NaN (Not a Number), since undefined can't be converted to a valid number.