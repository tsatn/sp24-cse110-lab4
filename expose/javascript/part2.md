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
    A. '3' + 2
        Output: '32'
        Explanation: The + operator, when used with a string and a number, converts the number to a string then concatenates them.
    
    B. '3' - 2
        Output: 1
        Explanation: The - operator converts the string '3' to a number and then performs subtraction.
    
    C. 3 + null
        Output: 3
        Explanation: null is treated as 0 in numeric operations, so 3 + 0 = 3.
    
    D. '3' + null
        Output: '3null'
        Explanation: null is converted to the string 'null', it is then concatenated with '3'.
    
    E. true + 3
        Output: 4
        Explanation: since true is treated as 1 in numeric operations, so 1 + 3 = 4.
    
    F. false + null
        Output: 0
        Explanation: Both false and null are treated as 0 in numeric contexts so the output is 0.
    
    G. '3' + undefined
        Output: '3undefined'
        Explanation: undefined is converted to the string then concatenated with '3'.
    
    H. '3' - undefined
        Output: NaN
        Explanation: undefined is treated as NaN in numeric operations. And Any operation with NaN results in NaN.

14. 
    A. '2' > 1
        Output: true
        Explanation: The string '2' is converted to the number 2, which is greater than 1.
        
    B. '2' < '12'
        Output: false
        Explanation: When comparing strings, '2' is lexically larger than '1' of '12'.
    
    C. 2 == '2'
        Output: true
        Explanation: == allows type coercion; the string '2' is converted to the number 2.
        
    D. 2 === '2'
        Output: false
        Explanation: === checks both value and type without allowing coercion.
    
    E. true == 2
        Output: false
        Explanation: true converts to 1, not 2, in numeric contexts.
    
    F. true === Boolean(2)
        Output: false
        Explanation: Although Boolean(2) is true, === checks for type identity, and Boolean(2) is not a literal but an object/converted value.

15. 
    ==: This equality operator checks if two values are equal, allowing for type conversion. That is, it can find different types of values equivalent as long as they can be converted to the same type.

    ===: This strict equality operator checks for equality without converting type. It evaluates both the value and the type. Where, if types differ, the result is automatically false, regardless what the value is.

16. 
    please go to expose/javascript/part2-question16.js

17.  
    The modifyArray function transforms each array element using the provided doSomething callback, effectively doubling each number in the input array. The final output is [2, 4, 6].

    When the function modifyArray([1,2,3], doSomething) is called:
    1. Initialization: 
        An empty array newArr is created.
    2. Processing:
        The function iterates through each element of the array [1, 2, 3].
        The doSomething callback is applied to each element, doubling it.
    3. Result:
        Results for each iteration are 2, 4, and 6, respectively, which are collected in newArr.
    4. Output:
        The function returns the modified array [2, 4, 6].

18.   
    please go to expose/javascript/part2-question18.js

19.  
    The outputs in the console will be in this sequence: 1, 4, 3, 2.






