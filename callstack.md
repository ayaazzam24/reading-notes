# Call stack
It’s a mechanism for an interpreter to keep track of its place in a script that calls multiple functions: specifically, what function is currently being run and what functions are called from within that function, etc When a script calls a function, the interpreter adds it to the call stack and then starts carrying out the function. Any functions that are called by that function are added to the call stack further up, and run where their calls are reached.

When the current function is finished, the interpreter takes it off the stack and resumes execution where it left off in the last code listing. If the stack takes up more space than it had assigned to it, it results in a “stack overflow” error.


# JavaScript
 About error messages debugging: To debug your JS code, the easiest and maybe the most common way its to simply console.log() the variables you want to check or, by using chrome developer tools, open your page with your JS code (press cmd+o in macOS or Ctrl+o in Windows) and choose your file to debug, click the line you wanna debug and refresh your page again (F5).


# What causes a stack overflow?
A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

# Types of error messages:
Reference errors: Syntax errors Range errors Type errors

Tools to avoid runtime errors:
You can only see whatever is wrong with your code after your run it. 1) eslint to make sure your style guide is consistency 2) TypeScript: make JS a more strong typed experience 3) quokka: to evaluate your code as you type’