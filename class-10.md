# ERROR HANDLING & DEBUGGING :
- The error messages that a browser gives look cryptic at first, but they can help you determine what
went wrong in your JavaScript and how to fix it. In this chapter you will learn about:
1. THE CONSOLE & DEV TOOLS :
Tools built into the browser
that help you hunt for errors.
2. ERROR HANDLING & DEBUGGING :
COMMON PROBLEMS Common sources of errors, and how to solve them.
3. HANDLING ERRORS :
How code can deal with
potential errors gracefully .


## - LOGGING DATA TO THE CONSOLE log :
write console.log();


![image](https://developers.google.com/web/tools/chrome-devtools/console/images/logtypeerror.png)

## - MORE CONSOLE METHODS :

1.  **conso1e. info()** can be used for general information.
2. **consol e.warn()** can be used for warnings.
3.  **console .error()** can be used to hold errors.

## - GROUPING MESSAGES :
you can use the **console. group ()** method to group the messages together , When you have finished writing out the results for the group, to indicate the end of the group the console .groupEnd () method is used.

## - WRITING TABULAR DATA :
 the **console. table ()** method lets you output a table showing:
• objects
• arrays that contain other
objects or arrays 

> You can create a breakpoint
in your code using just the
debugger keyword.

## - HANDLING EXCEPTIONS :
If you know your code might fail, use try, catch, and finally.
Each one is given its own code block.