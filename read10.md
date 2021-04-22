Eror handling and debuging

JavaScript can be hard to learn and everyone makes
mistakes when writing it. so wii learn
how to find the errors in your code. It will also know how
to write scripts that deal with potential errors gracefully.

ERROR OBJECTS

There are seven types of built-in error objects in
JavaScript:

+ Error
Generic error - the other errors
are all based upon this error
+ Syntax Error
+ Syntax has not been followed
ReferenceError
Tried to reference a variable that is
not declared/within scope
+ TypeError
An unexpected data type that
cannot be coerced
+ Range Error
Numbers not in acceptable range
+ URI Error
encodeURI ().decodeURI(),and
similar methods used incorrectly
+ Eval Error
eva l () function used incorrectly

![p](https://www.lambdatest.com/blog/wp-content/uploads/2018/03/TE.jpg)

## ERROR OBJECTS CONTINUED
+ Syntax Error
**SYNTAX IS NOT CORRECT**
This is caused by incorrect use of the rules of the
language. It is often the result of a simple typo.
+ ReferenceError
**VARIABLE DOES NOT EXIST**
This is caused by a variable that is not declared or is
out of scope.
+ EvalError
**INCORRECT USE OF eval() FUNCTION**
The eva l () function evaluates text through the
interpreter and runs it as code (it is not discussed
in this book). It is rare that you would see this type
of error, as browsers often throw other errors when
they are supposed to throw an Eva 1 Error.
+ URI Error
**INCORRECT USE OF URI FUNCTIONS**
If these characters are not escaped in URls, they will
cause an error: / ? & I : ;
## HOW TO DEAL WITH ERRORS
there are two things you can do with the errors:

1. DEBUG THE SCRIPT TO FIX ERRORS
If you come across an error while writing a script
(or when someone reports a bug), you will need to
debug the code, track down the source of the error,
and fix it.
2. HANDLE ERRORS GRACEFULLY
You can handle errors gracefully using try, catch,
throw, and fina1ly statements.

## A DEBUGGING WORKFLOW
First we ask **WHERE IS THE PROBLEM?**
1. Look at the error message, it tells you:
• The relevant script that caused the problem.
• The line number where it became a problem for
the interpreter.
• The type of error (although the underlying cause
of the error may be different).
2. Check how far the script is running.
Use tools to write messages to the console to tell
how far your script has executed.
3. Use breakpoints where things are going wrong.
They let you pause execution and inspect the va lues
that are stored in variables.

second **WHAT EXACTLY IS THE PROBLEM?**
1. When you have set breakpoints, you can see if the
variables around them have the values you would
expect them to. If not, look earlier in the script.
2. Break down I break out parts of the code to test
smaller pieces of the functionality.
• Write values of variables into the console.
• Calrfunctions from the console to check if they
are returning what you would expect them to.
• Check if objects exist and have the methods I
properties that you think they do.
3. Check the number of parameters for a function, or
the number of items in an array.

## CONSOLE METHODS
To differentiate between the
types of messages you write
to the console, you can use
three different methods. They
use various colors and icons to
distinguish them.
1. con so 1 e. info( ) can be used
for general information
2. consol e.warn( ) can be used
for warnings
3. console .error ( ) can be used
to hold errors