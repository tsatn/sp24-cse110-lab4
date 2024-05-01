1. The Issue is that the program treats all inputs as strings, leading to concatenation instead of arithmetic addition.

2. To resolve this, I changed the implementation by writting: result = parseInt(num1) + parseInt(num2). 
   This ensures that the inputs are converted to integers before being added together.
