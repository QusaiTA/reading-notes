## JavaScript:

**CH10:**

**stack:**  javaScript takes order line by line, and when need information from another variable below it stack.

> Each time a script enters a new execution context, there are two phases of activity:
- prapare: praparing a scope and creating the variable.
- excute: assigning process and run the code.

- **If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handl ing code.**
- **Error objects can help you find where your mistakes are and browsers have tools to help you read them.**

- **DEBUG THE SCRIPT TO FIX ERRORS** If you come across an error while writing a script, you will need to debug the code, track down the source of the error, and fix it.
- **HANDLE ERRORS GRACEFULLY** You can handle errors gracefully using try, catch, throw, and f i na 1 ly statements.

> **how to start debugging:**

- read the error massage.
- When you have set breakpoints, you can see if the variables around them have the values you would expect them to.
Break down I break out parts of the cod
- The JavaScript console will tell you when there is a problem with a script, where to look for the problem, and what kind of issue it seems to be.
- If you set multiple breakpoints, you can step through them one-by-one to see where values change and a problem might occur.