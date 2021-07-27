1. KEEP IT SHORT, STUPID!

You have read this a zillion times already. As a programmer/webmaster you might have applied this tip multiple times too but never forget this in case of JavaScript.
Use comments and white spaces while in development mode to keep your code readable.
Remove white spaces and comments before publishing your scripts in live environment. Also, try to shorten your variable and function names.
Consider using third party tools to compress your JavaScript code before publishing the same.

2.DEBUG JAVASCRIPT CODE

Even the best programmers make mistakes. To limit them, run your JavaScript code through a JavaScript debugger to make sure that you haven’t made any silly blunders that can easily be prevented.

3.MINIMIZE DOM ACCESS

DOM is one of the most complex APIs that slows down the code execution process. At times the webpage might not load or it might load incompletely. Better to avoid DOM.

4.LEARN JAVASCRIPT BEFORE USING JAVASCRIPT LIBRARIES

Internet is chock full of JavaScript libraries that perform various functions. Programmers end up using JavaScript libraries without understanding the side effects of the same. It is strongly advisable to learn the basics of JavaScript before using third party JavaScript libraries; otherwise, be prepared for disastrous results.

5.NEVER USE “VAR” MULTIPLE TIMES

While initializing every variable programmers tend to use “var” keyword. Instead, it is suggested that you use commas to avoid redundancy of keywords and reduce code size:
var variableOne = ‘string 1’,
variableTwo = ‘string 2’,
variableThree = ‘string 3’;

6.NEVER MISS SEMICOLONS

This is one of the programming bugs that can consume hours of debugging. Personally, I have spent hours looking for problems in my code when the reason was the missing semicolon.

7.Don't use ' == '

In JavaScript there are both '== ' and '===' and you might be used to "==" in other programming languages and might continue using the same, But using it without knowing how it works might bring few bugs which might be difficult to track. Read my previous article to know more.

8.Use Pure Functions

Pure functions is a function where everytime you call that function you get the same result and it should not have side effects.

Why should you care ?

This helps in testing the function and debugging becomes really easy. Understanding this wih an example would be better . Below is an impure function which multiples all values in an array by 2.

9.We developers are very lazy and usually use random names for variables and cry in a corner when we have to revisit the same code. You don't actually need to document your code if you have named things in the right way. Also use camel casing.

10.Use Destructing
Now if you want to access multiple values which are inside an object you use object destruction instead of manually writing extra lines of code.
