# ZeroDivisionError despite check
This JavaScript code demonstrates a subtle error in handling zero division.  Despite a seemingly correct check for zero values, the function still throws an error.
The issue lies in the order of operations and how JavaScript handles short-circuiting in logical OR.  When `b` is 0, the division operation still executes before the short circuit takes effect.
The solution below provides a more robust approach to safely handling potential division by zero.